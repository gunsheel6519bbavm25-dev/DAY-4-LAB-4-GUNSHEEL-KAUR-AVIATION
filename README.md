# DAY-4-LAB-4-GUNSHEEL-KAUR-AVIATION
Day 4 Generative AI lab on structured prompt engineering using Task, Context, Constraints and Output Format for aviation management scenarios.

Student: Gunsheel Kaur
Programme: BBA Aviation Management
Course: Generative AI for Business
Lab: Day 4 — Structured Prompt Engineering

Objective

The objective of this lab is to understand how structured prompts can improve the quality, relevance and reliability of Generative AI outputs in aviation management.

The lab focuses on four important prompt ingredients:

Task
Context
Constraints
Output Format

It also examines vague vs structured prompts, prompt testing, peer review and the importance of human verification.

Topics Covered
1. Vague Flight-Delay Prompt

A vague prompt such as:

"Write a message about a delayed flight."

does not provide enough information for an accurate and useful passenger communication.

Important missing information includes:

Flight number
Flight route
Delay duration
Verified reason for delay
Revised departure time
Passenger instructions
Tone
Word limit
Output format
Restrictions against invented information
2. Four Ingredients of a Good Prompt
Task

Clearly states what the AI needs to do.

Context

Provides relevant background and verified information.

Constraints

Defines limitations and tells the AI what it must or must not include.

Output Format

Specifies how the final response should be presented, such as an SMS, email, table or bullet-point list.

3. Structured Flight-Delay Prompt

The lab uses an aviation example involving flight AV205 from Delhi to Mumbai, delayed by 90 minutes due to adverse weather, with a revised departure time of 6:30 PM.

The prompt instructs passengers to monitor the airline's official application and airport display screens for updates.

The response is required to remain below 70 words, use a professional and reassuring tone, and avoid inventing information about gates, compensation, refunds, meals, hotels or airline policies.

4. Vague vs Structured Prompt

The structured prompt provides:

Complete flight details
Clear passenger instructions
Professional tone
Suitable response length
Specific output format
Restrictions against unsupported information

A structured prompt produces a response that is much closer to being ready for human review.

5. Baggage Complaint Analysis

A structured prompt was created to analyse passenger complaints related to:

Delayed baggage
Damaged baggage
Lost baggage
Staff communication
Tracking-information issues

The output is intended for management and must use only the complaints provided without inventing passenger details, figures or airline policies.

6. Aviation Prompt Challenge
Situation A — Flight Cancellation Email

A professional passenger email is created for a flight cancellation.

The prompt specifically prevents the AI from inventing:

Compensation
Refunds
Rebooking
Hotel
Meal
Other airline policies

It also requires a professional and empathetic tone.

Situation B — Airport Service Survey

A short passenger satisfaction survey is designed to measure:

Check-in
Security
Cleanliness
Signage
Staff behaviour

The survey uses a simple 1–5 rating scale and includes an optional open-ended question.

7. Peer Review

The prompt was reviewed for:

Clear task
Sufficient context
Specific constraints
Output format
Intended audience
Prevention of unsupported assumptions
Testable instructions
Sensitive information

The revised prompt requires the AI to use only verified information, follow the requested tone and word limit, and avoid inventing operational details or airline policies.

8. One Variable Test

The effect of changing one prompt component was tested by changing the output format from SMS to email.

The information and constraints remained the same, while the email format resulted in a longer and more detailed response.

Key Learnings
A clear task helps AI understand what needs to be done.
Context makes AI responses more specific and useful.
Constraints reduce unsupported assumptions.
Output format controls how the response is presented.
Structured prompts produce more relevant and reviewable outputs.
Changing one prompt component at a time helps identify its effect.
Peer review can identify missing information and unclear instructions.
A well-structured prompt cannot guarantee factual accuracy.
Human verification is still required for flight status, operational information, departure times and airline policies.
Conclusion

This lab demonstrated that effective prompt engineering is important when using Generative AI in aviation management. Structuring prompts with Task, Context, Constraints and Output Format improves clarity and usefulness while reducing the risk of unsupported information.

However, AI-generated aviation information still requires human verification before it is used for operational or passenger-facing purposes.

Files Included
LAB4-GUNSHEEL KAUR-2520996519.docx
README.md
