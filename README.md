# Risk-based Authentication Dataset
Dataset related to User Login Logs, in order to do AI model training of Risk-based Authentication combined with Large Language Model (LLM).

# Data Description in login_logs.csv
1. id : Primary key ID from MySQL
2. email: User's email
3. ip : IP used by user when logging in
4. country: User's country location when logging in. Extracted from Latitude and Longitude.
5. latitude: User's latitude location when logging in.
6. longitude: User's longitude location when logging in.
7. user_agent: User's user agent or browser used when logging in.
8. platform: User's platform (Windows, android, iPhone, etc) used when logging in.
9. screen_width: User's screen width size when logging in.
10. screen_height: User's screen height size when logging in.
11. cookies_enabled: User's has cookie enabled or not when logging in. 1 or 0 value.
12. fingerprint: User's device fingerprint when logging in. Combination of user_agent, screen_width, and screen_height.
13. timestamp: User's timestamp when logging in.
14. gemini_explanation: explanation from Gemini for amber cases. Red and Green final outcome's explanation will be stored after successfully login or successfully enter OTP for red cases.
15. risk_breakdown: breakdown score of final risk score.
16. risk_score: final risk score.

# Authors
- Fernando Morientes
- Fachry Altair Gantari Amaludin
- Griffin Koh
- Christopher Limawan
