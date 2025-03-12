# Resume-Analyser-AI
📝 Resume Analyzer AI – Your Smart Career Assistant! 🤖💡
🚀 About This Project:
Finding the right job can be tough, especially when your skills don’t exactly match the job description. That’s where Resume Analyzer AI comes in! This AI-powered tool analyzes a resume against a given job role and provides a structured insight into skill matches, gaps, and potential alternative career paths.

With just two inputs – a PDF resume file path and a job role (string) – this notebook processes the resume and delivers:
✅ Key Strengths & Observations – Highlights the resume’s strong skills.
✅ Job Match Analysis – Compares resume skills with the job role.
✅ Skill Gap Insights – Lists missing skills & how to bridge the gap.
✅ Alternative Career Suggestions – If the resume isn’t a good fit, it suggests better roles!

Tech Stack & Tools Used:
SentenceTransformers – Generating embeddings for similarity comparison
ChromaDB – Storing & retrieving vectorized data
Llama2 / Mistral / OpenHermes-2.5 – LLMs tested for best results
Gradio and FastAPI – Simplified UI service for user interaction (not available in the current code)


How to Use:
1️⃣ Provide the path to a PDF resume
2️⃣ Enter the job role as a string
3️⃣ Run the notebook and get the analysis report!

Future Improvements:
✅ Once more fine-tuned, coming up with UI interaction service
✅ Integration with ATS (Applicant Tracking Systems)
✅ More advanced resume parsing
