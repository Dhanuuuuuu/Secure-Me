# Secure-Me
Where Identity Meets Context

Secure-Me is a risk-based authentication framework designed to protect digital banking systems from AI-powered impersonation and deepfake attacks. It verifies not only the user's identity but also ensures that a real human is physically present during authentication.

# Problem
Traditional banking authentication methods, such as OTP and static biometrics, are increasingly vulnerable to deepfake technology. Attackers can clone faces, replay videos, or impersonate users during high-value transactions.

# Solution
Secure-Me introduces a multi-signal authentication system that combines:
                                            Face verification
                                            Active liveness detection
                                            Device fingerprinting
                                            Private gesture authentication
                                            
A central risk engine analyzes these signals and classifies actions as low, medium, or high risk before granting access.

# Key Features
Active Liveness Detection using screen brightness changes
Device Fingerprinting to recognize trusted devices
Private Gesture Authentication for additional security
Risk Scoring Engine that aggregates all signals

# Tech Stack
Frontend: React / Android
Backend: Python (FastAPI / Flask)
AI/ML: OpenCV, TensorFlow / PyTorch, MediaPipe
Database: PostgreSQL / MongoDB
