# 📊 Thanawya Amma Data Analysis (Egyptian Ministry of Education)

## 📌 Important Data Context & Methodology
This data analysis is based on real datasets belonging to the Egyptian Ministry of Education. The data was extracted from official Excel and non-Excel files. 

**Handling Missing Data:**
Some missing information, specifically the detailed breakdown of the different educational sections, was supplemented using official statements from the Ministry of Education and the state-owned "Al-Youm Al-Sabea" (Youm7) newspaper. 

**Data Anomaly Note:**
During the cleaning process, it was observed that some successful students had a recorded score of "0". This occurred because the Egyptian Ministry of Education grants a "pass" status to students with valid medical (or similar) excuses. To maintain data integrity, these "0" scores for successful students were replaced with `null` values.

---

## 📈 General Overview & Reports

**Overall Statistics:**
* **Total Registered Candidates:** 919,000 students
* **Total Attendees:** 893,000 students
* **First Session Success Rate:** 70.8%
* **Second Session (Round 2) Candidates:** 22.9%
* **Failure Rate (Repeating the year):** 5.82% (Failed in more than two subjects)

**Score Distribution Insights:**
The score distribution graph shows that the vast majority of students fall within the **160 to 200 marks** range. The curve begins to slope downward on both sides of this peak, indicating that the highest concentration of scores ranges between **50% and 62.5%**.

**💡 Summary & Takeaway:**
The data strongly suggests that this year's exams leaned towards being upper-intermediate to difficult. This is clearly reflected in the score distribution graph, despite the fact that the actual student curriculums range from easy to hard.
<h3 align="center">1. General Overview & Distribution Curve</h3>
<p align="center">
  <img src="Screenshot%20(11).png" alt="General Distribution" width="850">
</p>
---

## 📐 Section-Wise Analysis

### 1. Mathematics Section (شعبة الرياضيات)
* **Performance:** This section achieved the highest success rate among all sections, despite having the lowest number of enrolled students.
* **Exam Difficulty:** Paradoxically, it is widely reported that their exams were the hardest compared to other sections, particularly in Pure Mathematics and Chemistry. 
* *(Note: Refer to the dashboard for the names of the top-ranking students in this section).*
* **💡 Summary:** Statistically, this is the safest section for securing high grades.
<h3 align="center">2. Math Section Statistics</h3>
<p align="center">
  <img src="Screenshot%20(12).png" alt="Math Section" width="850">
</p>
### 2. Arts Section (الشعبة الأدبية)
* **Performance:** This section recorded the highest failure rate, even though their exams were generally considered to lean towards the easier side.
* *(Note: Refer to the dashboard for the names of the top-ranking students in this section).*
* **💡 Summary:** This is considered the hardest or most exhausting section due to the massive amount of memorization required and the highly dense, packed curriculum.
<h3 align="center">3. Arts Section Statistics</h3>
<p align="center">
  <img src="Screenshot%20(13).png" alt="Arts Section" width="850">
</p>
### 3. Scientific / Biology Section (شعبة علمي علوم)
* **Performance:** This is the largest section by a wide margin, sweeping the majority of the student population. They recorded a satisfactory success rate, slightly better than the Arts section.
* **Exam Difficulty:** Their exams were categorized as intermediate to upper-intermediate. The "upper-intermediate" aspect is largely because they shared the same difficult Chemistry exam with the Math section.
* **Top Performers:** As shown in the data, the top-ranking students are heavily clustered around the exact same high scores due to the sheer volume of students in this section.
* **💡 Summary:** This is the most balanced section in terms of curriculum and opportunities. It is not as analytically difficult as the Math section, nor is it as mentally exhausting regarding memorization as the Arts section.
<h3 align="center">4. Scientific Section Statistics</h3>
<p align="center">
  <img src="Screenshot%20(14).png" alt="Scientific Section" width="850">
</p>
---

## 🔄 Second Session (Round 2) Analysis

* **Participation:** Approximately 25% of the total 919,000 students retook exams in the second session.
* **Attendance & Success:** Almost all eligible students attended. The session recorded a very high success rate of **92.12%**.
* **Overall National Pass Rate:** When combining the first and second sessions, the total success rate reached **91.90%** of the original 919,000 students.

**Graph Insights (The 50% Spike):**
The visual graph for the second session shows a massive, defining spike exactly at the **160-mark limit (50%)**. There is a very valid reason for this: the Ministry grants "mercy marks" (درجات رأفة) to push students just over the passing threshold to prevent them from failing and repeating the entire academic year.

**💡 Summary:**
The second session witnessed a highly successful leap in preventing mass student failure.
<h3 align="center">5. Second Session Analysis</h3>
<p align="center">
  <img src="Screenshot%20(17).png" alt="2nd Session" width="850">
</p>
