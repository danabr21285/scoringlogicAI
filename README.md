# 🎯 Prompt-Driven Scoring Logic with OpenAI
### Data-Informed Decision Support Using Natural Language Intelligence

This project demonstrates how you can use the power of **OpenAI’s large language models** to generate structured, data-informed scoring rubrics from real-world tabular data. Built using 4 years of student admissions data from a graduate healthcare program, this approach is widely adaptable to any business looking to **understand customer behavior, prioritize leads, or guide strategic decisions** using transparent, explainable scoring.

---

## 🧠 Project Concept

> How can we design a scoring model that reflects the behaviors, patterns, and characteristics of people who **actually took action** like enrolling, purchasing, donating, or subscribing?

This project uses structured prompts and a CSV-formatted dataset of student profiles to instruct OpenAI's GPT model to:

- Identify trends among successful "conversions" (students who enrolled)
- Detect common themes in qualitative data (like essays, Schools Attended, majors)
- Detect common themes in quantitative data (like age, distance from campus, GPAs, shadowing/volunteer/heath realted employment experience hours)
- Generate a detailed, **weighted scoring rubric** based on historical patterns
- Explain the **rationale** behind scoring choices
- Provide **implementation recommendations** for admissions or business workflows
- Ensure reccommendations are **data-informed, ethically sound, and adaptable** for annual updats as trends evovle 
---

## 🛠️ Tech Stack

- **Python** + **Jupyter Notebook**
- **Pandas** for data handling
- **OpenAI GPT-4o API** for prompt-driven logic creation
- (Optional) **Excel or CSV files** for data input

---

## 🧩 What Makes This Project Unique?

- ✅ **No machine learning experience required**
- ✅ **Transparent logic** — everything is human-readable and editable
- ✅ **Customizable prompts** tailored to your domain
- ✅ **Qualitative + quantitative analysis** in one model
- ✅ **Fast deployment** — update scores by rerunning the notebook with new data

---

## 💼 Broader Business Use Cases

| Sector | Example |
|--------|---------|
| Higher Ed | Prioritize applicants most likely to enroll |
| SaaS | Score trial users based on onboarding patterns |
| Nonprofits | Rank donors based on giving history and email engagement |
| Healthcare | Score patients for follow-up based on risk and outreach data |
| HR/Recruiting | Identify applicants aligned with organizational values |

---

## 📊 How It Works

1. **Load the Data**: Format your admissions, customer, or user data as a Pandas DataFrame.
2. **Define the Prompt**: Write a detailed prompt that:
   - Sets the business context
   - Instructs the model to identify patterns
   - Requests a clean scoring rubric and rationale
3. **Call OpenAI API**: Send the system/user messages using `client.chat.completions.create(...)`.
4. **Receive Results**: The response includes:
   - Trend summary
   - Scoring table
   - Rationale for weights
   - Implementation ideas
5. **Apply the Rubric**: Use it to score future users, applicants, or leads.

---

## 🔐 Ethical Considerations

- Focus on variables that are **relevant, accessible early**, and **ethically sound**  
- Avoid overfitting to past trends that may reflect bias  
- Regularly **audit and adapt** the rubric based on updated data

---

## 🚀 How to Use

1. Install requirements  
   ```bash
   pip install pandas openai openpyxl
   ```
2. Add your OpenAI key and data file path in the notebook
3. Run all cells to generate your custom rubric

---

## 🔮 Future Improvements

- Add support for multiple prompt versions (A/B testing)
- Integrate with CRM or admissions systems for real-time scoring
- Use GPT to auto-generate email or dashboard summaries
- Build a Streamlit interface for non-technical teams

---

## 👤 Author

**Dana Brooks**  
Executive Director of Admissions | Data Strategist | Prompt Engineer  
GitHub: [@danabr21285](https://github.com/danabr21285)
