Batch: B2  
Roll No: 16014223105  
Subject: MLCS  

# MLCS_Exp2
# ==============================================================
# MLCS LAB
# Title: Defining a Machine Learning Problem for Anomaly Detection
#        in Cloud Security Logs
# Type: Read-Only Documentation Code (For GitHub Repository)
# ==============================================================


# --------------------------------------------------------------
# 1. Understand the Problem Domain
# --------------------------------------------------------------
# Cloud cybersecurity focuses on protecting cloud platforms from
# digital threats such as unauthorized access, abnormal API usage,
# insider threats, and suspicious network activity.
#
# Cloud systems generate large volumes of logs including login
# records, API requests, and resource access history. Traditional
# rule-based monitoring struggles to detect unknown attacks.
# Machine learning helps identify anomalies by learning normal
# behavioural patterns.


# --------------------------------------------------------------
# 2. Articulate the Problem Statement
# --------------------------------------------------------------
# Problem Statement:
# Develop an unsupervised machine learning model that analyzes
# cloud security logs and detects anomalous activities that may
# indicate cyber threats.
#
# Task Type: Anomaly Detection
# Learning Approach: Unsupervised Learning
# Business Goal: Improve cloud threat monitoring and reduce
# manual security analysis.


# --------------------------------------------------------------
# 3. Identify Input Data Requirements
# --------------------------------------------------------------
# Required Data Features:
#
# - Authentication logs:
#   * Login timestamps
#   * Failed login attempts
#
# - API activity logs:
#   * Request frequency
#   * Service usage patterns
#
# - Network metadata:
#   * Source IP
#   * Geolocation
#
# - Resource access logs:
#   * File access history
#   * Permission changes
#
# Data Format:
# - CSV or JSON log files
#
# Data Sources:
# - AWS CloudTrail style datasets
# - Azure/GCP log datasets
#
# Bias and Privacy Considerations:
# - Remove sensitive personal data
# - Ensure diverse user behaviour patterns


# --------------------------------------------------------------
# 4. Define Output Requirements
# --------------------------------------------------------------
# Output:
# - Anomaly Score
#   0 → Normal activity
#   1 → Suspicious activity
#
# Evaluation Metrics:
# - Precision
# - Recall
# - F1-score
#
# Interpretability:
# - Visualization of anomaly scores
#
# Performance Requirement:
# - Real-time or near real-time detection capability


# --------------------------------------------------------------
# 5. Establish Constraints and Assumptions
# --------------------------------------------------------------
# Constraints:
# - Large-scale cloud log data
# - Limited labeled attack datasets
# - Privacy and compliance requirements
#
# Assumptions:
# - Most log data represents normal behaviour
# - Anomalies are rare deviations
#
# Ethical Consideration:
# - Maintain user privacy
# - Avoid excessive false alerts


# --------------------------------------------------------------
# 6. Evaluate Feasibility and Impact
# --------------------------------------------------------------
# Feasibility:
# - Suitable models:
#   * Isolation Forest
#   * One-Class SVM
#   * Autoencoders
#   * DBSCAN Clustering
#
# Impact:
# - Early detection of suspicious cloud activity
# - Reduced manual monitoring effort
# - Improved cloud security posture


# --------------------------------------------------------------
# 7. Document and Refine
# --------------------------------------------------------------
# Documentation:
# - Maintain structured README files
#
# Version Control:
# - Use GitHub for tracking updates
#
# Refinement:
# - Update datasets regularly
# - Improve models as new threats emerge


# ========================== END ===============================
