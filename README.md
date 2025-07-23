# 📧 Email Subject Filter - Keyword: "Lead"

This Python script filters and prints email subjects that contain the word **"Lead"** (case-insensitive).

## 📌 Example

### Input:
emails = [
"New Lead from Form",
"Daily Report",
"Zoom Invite",
"Cybersecurity Lead"
]


### Output:
New Lead from Form
Cybersecurity Lead


## 🚀 How to Run

1. **Clone the repository**:

git clone https://github.com/deckardshaw77/email-filter.git
cd email-filter


2. **Run the script**:

python filter_leads.py

text

Make sure you have **Python 3.x** installed.

## 🛠 Customization

- To search for a different keyword, just modify this line:
if "lead" in subject.lower():

Replace `"lead"` with any keyword you want.

- You can also change the subject list directly in the `emails` array.

## 💡 Use Case

Useful for filtering marketing, sales, or CRM emails that contain leads and need urgent attention.
