# Risk Register - Job Match-Making System

## Potential Challenges & Our Response Plan

Here are the main risks we've identified that could impact our project timeline, budget, or final outcome. We've scored each risk based on how likely it is to happen and how much impact it would have if it did occur.

| Risk ID | What Could Go Wrong | Category | Likelihood (1-5) | Impact (1-5) | Risk Score | Our Approach |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| R1 | **Our resume data isn't good enough** - If the training data is messy or too small, our AI models won't learn properly | Technical | 4 | 5 | 20 | Take proactive steps to prevent |
| R2 | **Cloud computing costs spiral out of control** - Model training might take longer and use more expensive resources than we budgeted for | Cost | 3 | 4 | 12 | Take proactive steps to prevent |
| R3 | **The matching algorithm isn't smart enough** - The core logic might not produce matches that actually make sense to users | Technical | 3 | 4 | 12 | Take proactive steps to prevent |
| R4 | **A key team member becomes unavailable** - Especially during critical phases like development or system integration | Resource | 2 | 5 | 10 | Share the risk |
| R5 | **Backend and frontend don't play nice together** - APIs might not communicate properly, causing system errors | Technical | 3 | 3 | 9 | Take proactive steps to prevent |
| R6 | **Feature requests keep expanding** - New UI features or changes requested late could delay our timeline | Stakeholder | 2 | 4 | 8 | Accept and manage |
| R7 | **Users aren't happy with the final system** - During testing, users might find the system difficult to use or too slow | Stakeholder | 2 | 3 | 6 | Take proactive steps to prevent |

## Our Top 3 Risks & How We'll Handle Them

### 🚨 1. R1 - Poor Quality Training Data
This is our biggest concern because everything depends on good data.

**Our Game Plan:**
- Build strong data cleaning processes from the start
- Look for additional resume datasets on platforms like Kaggle if we need more data
- Use text augmentation techniques to make the most of the data we have
- **Who's responsible:** Tee Kai En
- **Deadline to secure good data:** November 18, 2025 (before we start serious model training)

### 💰 2. R2 - Cloud Costs Blowing Up
AI training can get expensive fast if we're not careful.

**Our Game Plan:**
- Keep a close eye on GPU usage with regular monitoring
- Set up billing alerts so we know immediately if costs are rising
- Use cheaper cloud instances when possible (like spot instances)
- Optimize our training code to be more efficient
- **Who's responsible:** Muhammad Aiman
- **Deadline for cost controls:** December 10, 2025 (before intensive training begins)

### 🎯 3. R3 - Matching Algorithm Isn't Accurate Enough
If the matching doesn't work well, the whole system fails.

**Our Game Plan:**
- Test the algorithm logic early with simple prototypes
- Keep improving how we calculate similarity between jobs and candidates
- Have a backup plan - a simpler keyword-matching approach we can use if needed
- **Who's responsible:** Tee Kai En
- **Deadline for algorithm validation:** December 20, 2025 (during the design phase)

## Connecting Risks to Our Schedule

**Where We'll Check Quality:**
- After we finish collecting and cleaning data (Task 2.2)
- After training our OCR and NLP models (Task 4.4)
- After testing matching accuracy (Task 5.4)
- After putting all the system pieces together (Task 7.2)

**High-Risk Areas in Our Timeline:**
- **Data Collection Phase:** Where we're most worried about data quality (R1)
- **AI Development Phases:** Where model performance and cloud costs are biggest concerns (R1, R2, R3)
- **System Integration Phase:** Where technical connections between components might fail (R5)

We've reviewed our project schedule and made sure we have some extra time built in for fixing model issues and solving integration problems that might come up.
