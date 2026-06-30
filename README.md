# AI/ML Club - Next Day SF Predictions

**Academic Year:** 2025-2026 Fall Semester  
**Project Duration:** Febraury 2026 - May 2026

## Project Description

The goal of our project is to build on the idea of navigation apps like Waze by using machine learning models to predict next-day traffic patterns. Many people struggle to know when to leave for important meetings, school, work, or appointments because traffic can be unpredictable. Our system helps users plan their travel ahead of time by giving them traffic predictions for the next day, allowing them to make better decisions about when to start their trip.

**Key Objectives:**
- Predict Next Day Traffic Conditions in San Francisco
- Build a XGBoost model that can accurately learn patterns from the data and make reliable predictions.
- Use DynamoDB to store the model predictions
- Using React for website display and python for backend implementation.

## Lead Contact Information

**Project Lead:** Srihan Cheemangunta  
📧 Email: srihan.cheemangunta@sjsu.edu 
💼 LinkedIn: https://www.linkedin.com/in/srihanrc/  
📱 Phone:   661-373-8186

**Faculty Advisor:** [Advisor Name]  
📧 Email: [advisor.email@university.edu]  
🏢 Office: [Building Name, Room Number]

## Contributors

*For detailed member information including LinkedIn profiles and Discord handles, see [docs/members.csv](docs/members.csv)*

| Name | Role | Email | GitHub |
|------|------|-------|--------|
| Srihan Cheemangunta | Project Lead & Model Construction | srihan.cheemangunta@sjsu.edu | https://github.com/srihanrc |
| Purva | Model Construction | purvarhishikesh.babar@sjsu.edu | https://github.com/Purvab07 |
| Sean Sheng | Website Developer | shih-ru.sheng@sjsu.edu | https://github.com/LightBlueJacketStudio |
| Shruthi | Website Developer | shruthi.raghavan@sjsu.edu  | https://github.com/RShruthiCS |

## Project Kanban Board

**🔗 Public Board:** [View our Kanban Board](https://github.com/aiml-club/[repo-name]/projects/1)

https://github.com/srihanrc/Next-Day-SF-Predictions

## Repository Structure

```
[project-repo-name]/
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
├── docs/
│   ├── members.csv             # Team member details with LinkedIn & Discord
│   ├── info.json               # Project metadata for website automation
│   ├── thumbnail.webp          # Project thumbnail image
│   └── pitch_slides.pdf        # Project presentation slides
└── [additional_folder]/
```

''' 
[backend]
    - app.py
    - loaddb.py
    - models.py
    - seedData.py
[frontend]
   [public]
      - favicon.svg
      - icons.svg
   [src]
      [assets]
         - App.css
         - App.jsx
         - index.css
         - main.jsx
   - .gitignore
   - README.md
   - eslint.config.js
   - index.html
   - package-lock.json
   - package.json
   - requirements.txt
   - vite.config.js
- .gitignore
- README.md
- SF_XGBoost_Model.ipynb
- package-lock.json
- package.json
- requirements.txt  
   
'''    

## Quick Start Guide

### Prerequisites
- Python 3.8 or higher
- Git
- React libraries installed
- install npm

### Installation Guide

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aiml-club/[repo-name].git
   cd [repo-name]
   ```
      git clone https://github.com/srihanrc/Next-Day-SF-Predictions.git
      cd Next-Day-SF-Predictions
   '''
      git clone 
3. **Create virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   pip install flask flask-cors joblib pandas numpy scikit-learn xgboost peewee psycopg[binary] python-dotenv
   '''
      npm create vite@latest my-react-app -- --template react
      cd my-react-app
      npm install
   '''
5. **[Additional setup step]:**
   ```bash
   [command or instruction]
   ```

## Technology Stack

- **Programming Language:** Python, Javascript, React
- **ML/AI Libraries:** XGBoost Regression, Scikit-learn
- **Development:** VS Code, Jupyter Notebook, Github
- **Version Control:** Git & GitHub
- **[Category]:** Frontend - React, Backend - Flask, PostgreSQL, Python
- **Database:** Flask, PostgreSQL
- **Deployment:** Website with 3 webpages

## License

This project is licensed under the [License Type] License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- PyCaret github for traffic dataset
- [Acknowledgment 2]
- [Acknowledgment 3]

---

**Last Updated:** 3/27/2026  
**Next Review:** [Date]

---

*This README follows the AI/ML Club standard template. For questions about the template or suggestions for improvements, contact the club leadership team.*
