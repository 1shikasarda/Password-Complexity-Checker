# *Password Complexity Checker*🔒
## *Overview*
Build a tool that assesses the strength of a password based on criteria such as length, presence of uppercase and lowercase letters,numbers, and special characters and provide feedback to users on the password's strength. This Python script provides a comprehensive assessment of password strength by evaluating multiple security criteria. It offers actionable feedback to help users create more secure passwords.

## *Features*
- Multi-factor evaluation of password strength 🔍
- Detailed feedback with specific improvement suggestions 📝
- Interactive mode for testing multiple passwords 🔄
- No external dependencies (uses only Python standard libraries) 📚
- Configurable criteria (can be modified in the code) 🔧
- Immediate results with clear strength indicators 📊
- No network calls: Works completely offline 📴

## *Password Strength Criteria*
The checker evaluates these aspects (all equally weighted):
- Criteria: Minimum Requirement, Recommended
- Length: 8 characters, 12+ characters 📏
- Uppercase letters: At least 1, Mixed case 🔠
- Lowercase letters: At least 1, Mixed case 
- Numbers: At least 1, 2+ numbers 🔢
- Special characters: At least 1, 2+ special chars 🔤

## *Scoring System:
The password receives a score from 0-4 based on meeting these criteria:
- 4/4: "Strong password! Keep it safe." 🎉
- 3/4: "Good password but could be stronger." 👍
- 2/4: "Moderate password. Consider improvements." 🤔
- 1/4: "Weak password." ⚠️
- 0/4: "Very weak password." 🚨
