# jlpt-study-quiz
JLPT Study quizzes

This web app is used as a study guide for all JLPT levels.

The quizzes and notes will be based on freely available in the web JLPT resources.

This web app will only serve as a guide and a supplementary resource for studying for the exam.
*_Do not treat at as a source of truth_*

# How to contribute
Generate a `quiz_data.json` based on the structure below:
```
[
    {
        "question": "question',
        "options": ["option 1",
                    "option 2",
                    "option 3",
                    "option 4"],
        "answer": "answer matches one of the strings in options array"
    }
]
```

Open a PR with the json and specify which section the quiz will be placed in.

# Disclaimer
All of the questions are generated using Google Gemini based on freely available in the web JLPT resources.

Feel free to open issues or PRs to address any discrepancies or wrong information in the quiz.