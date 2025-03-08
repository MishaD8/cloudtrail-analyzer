# 🔍 CloudTrail Log Analyzer

## 📖 Description
This project contains a Python script that analyzes **AWS CloudTrail logs** to detect suspicious activities and generate a security report.

## 🎯 Project Goals
- Download CloudTrail logs using AWS CLI.
- Analyze logs for suspicious patterns (e.g., mass object deletions, changes to critical IAM roles).
- Automatically generate a security incident report.

## ⚙️ Technologies Used
- AWS CLI
- Python (boto3, pandas)
- JSON (log files)

## 📂 Files
| File | Description |
|---|---|
| cloudtrail_analyzer.py | Main analysis script |
| suspicious_patterns.json | JSON file with suspicious activity patterns |
| README.md | Project documentation |

## 🚀 How to Use
1. Make sure AWS CLI is configured.
2. Download CloudTrail logs (using CLI or Console).
3. Run analysis:  
   `python cloudtrail_analyzer.py --log-folder ./cloudtrail-logs/`
4. Review generated `incident_report.csv`.

## 🔗 Useful Links
- [AWS CloudTrail Documentation](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
- [boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
