# 📊 Earnings Call Transcripts Dataset

This repository contains a collection of **earnings call transcripts** from publicly traded companies. These transcripts provide insights into a company's financial performance, executive outlook, and market sentiment, making them valuable for **Natural Language Processing (NLP), sentiment analysis, and financial forecasting**.

## 📂 Dataset Structure

```plaintext
earning_call_dataset/
│── dataset/
│   ├── ADM_q1_2021.txt       # Earnings call transcript for Archer Daniels Midland (Agribusiness, Q1 2021)
│   ├── AIG_q1_2021.txt       # Earnings call transcript for American International Group (Insurance/Financial, Q1 2021)
│   ├── CVX_q4_2021.txt       # Earnings call transcript for Chevron Corporation (Energy, Q4 2021)
│   ├── ...                   # More earnings call transcripts
│── scripts/                 # Python scripts for processing data
│── README.md                # Documentation
```

### **JSON File Structure**
Each earnings call transcript is stored in JSON format, containing **prepared remarks, Q&A sessions, and participant information**.


```json
{
  "header_texts": [
    "Contents:",
    "Prepared Remarks:",
    "Questions and Answers:",
    "Call participants:"
  ],
  "prepared_remarks": [
    {
      "speaker": "Douglas A. Lindsay",
      "speech": "Thanks, Mike and thank you for joining us today. I'm very pleased with the strong start to 2021..."
    }
  ],
  "q_and_a": [
    {
      "speaker": "Operator",
      "speech": "Anthony Chukumba with Loop Capital Markets, your line is open."
    }
  ],
  "participants": [
    "Douglas A. Lindsay--Chief Executive Officer",
    "C. Kelly Wall--Chief Financial Officer",
    "Steve Olsen--President"
  ]
}
