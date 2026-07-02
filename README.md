# Course-doer
Project: Coursera Course Automation Bot

Context

I am an employee at Coursera working on security vulnerability testing. We need to develop an automated testing bot to identify security gaps in our course completion workflow. This bot will simulate potential automated attacks that malicious actors could use to bypass course security measures.

Objective

Build an automated bot that:

1. Authentication Flow
   · Log into the Coursera mobile app using valid test credentials
   · Handle any authentication challenges (2FA, captcha, etc.)
2. Course Automation
   · Navigate to any selected course
   · Automate through all course content (videos, quizzes, readings, assignments)
   · Bypass any security checkpoints that prevent rapid course progression
   · Successfully complete the course and generate a certificate
3. Scoring System
   · For each successful certificate generation: Score = -10 (indicates security vulnerability found)
   · For each blocked certificate generation: Score = +10 (indicates security measure working)
   · Display real-time scores on the UI dashboard
4. Security Analysis
   · Log all attempted bypasses and their success/failure rates
   · Generate a comprehensive report identifying weak points
   · Provide actionable recommendations to improve security against AI-driven automation attacks
