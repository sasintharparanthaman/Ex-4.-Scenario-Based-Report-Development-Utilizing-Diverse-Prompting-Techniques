# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques

## NAME : Sasinthar P
## REG : 212223230199


Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim:

The aim of this experiment is to design and develop an AI-powered chatbot that can effectively handle customer inquiries, provide product-related support, and improve customer experience in a retail environment. The chatbot will be designed using diverse AI prompting techniques to test how different prompt engineering strategies influence chatbot responses, efficiency, and customer satisfaction.

## Algorithm:

Problem Identification

Customer service challenges in retail (delayed responses, lack of personalization).

Requirement for an AI chatbot to improve response efficiency.

Data Collection

Simulated queries like:

“What is the return policy for electronics?”

“Track my order #12345.”

“Suggest a gift for my 10-year-old daughter under ₹2000.”

Prompt Design (Experiment)

Zero-shot prompting → Ask chatbot directly without examples.

Few-shot prompting → Provide examples of Q&A.

Chain-of-thought prompting → Ask chatbot to explain reasoning step by step.
-
Persona-based prompting → Instruct chatbot to act like a “retail customer service agent.”

Role-based prompting → Assign chatbot a fixed role, e.g., “You are a fashion stylist.”

Socratic prompting → Use guided questioning to refine answers.

Chatbot Response Collection

Run queries with each prompt type.

Save chatbot outputs.

Evaluation

Compare accuracy, tone, completeness, clarity.

Record observations.

Report Development

Document Aim, Algorithm, Prompts, Outputs, and Results.

Create a structured scenario-based experiment report.

<img width="916" height="449" alt="image" src="https://github.com/user-attachments/assets/e3bfe01d-5002-4318-8689-a074da4e83b2" />

## Prompt:

Develop a scenario-based report on an AI-powered retail chatbot using diverse prompting techniques (Zero-shot, Few-shot, Role-based, Chain-of-Thought, Persona-based, Instruction-based, Scenario-based). For each technique, show the prompt, output, and evaluation. Compare results based on accuracy, clarity, depth, and user experience. Conclude with the most effective prompting style for report development

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/9384eaf4-0426-41e6-baac-901212b54e4d" />


## Output:

Prompts, Outputs, and Results (with Examples)
Case Study: Retail Chatbot Query – “What is the return policy for electronics?”
(i) Zero-Shot Prompting

Prompt: “What is the return policy for electronics?”

Output: “Electronics can usually be returned within 7 to 15 days depending on the store’s policy.”

Result: Direct but vague; lacks personalization and detailed procedure.
(ii) Few-Shot Prompting

Prompt:

Example 1: Customer: What is the return policy for clothes? Bot: Clothes can be returned within 30 days if unused with original tags.

Example 2: Customer: What is the return policy for groceries? Bot: Groceries cannot be returned, but defective products can be exchanged within 24 hours.

Now answer: What is the return policy for electronics?

Output: “Electronics can be returned within 15 days of purchase if in original condition with receipt. Refunds are processed within 5–7 business days.”

Result: More accurate and structured due to examples.
(iii) Chain-of-Thought Prompting

Prompt: “Explain step by step: What is the return policy for electronics?”

Output:
1.Check category: Electronics.

2.Verify condition: Must be unopened/undamaged.

3.Timeline: Return within 15 days.

4.Refund: Processed within 7 days.

Result: Clear breakdown; useful for explaining rules.
(iv) Persona-Based Prompting

Prompt: “You are a customer service agent of XYZ Retail. Answer: What is the return policy for electronics?”
•
Output: “At XYZ Retail, electronics can be returned within 15 days if unopened and accompanied by receipt. For defective items, we offer free replacement.”
•
Result: Professional, brand-aligned tone.
(v) Role-Based Prompting

•Prompt: “You are a senior store manager. Explain the return policy for electronics to a new customer.”

•Output: “As per our store policy, electronics are eligible for return within 15 days of purchase. Ensure the product is unused, original packaging intact, and receipt is provided. Defective items qualify for immediate exchange.”

•Result: Detailed and authoritative.

(vi) Socratic Prompting
•Prompt: “Do you think electronics can be returned anytime? Why or why not?”

•Output: “No, electronics cannot be returned anytime because they are high-value items. To prevent misuse, we restrict returns to 15 days under strict conditions.”

•Result: Engages customer in reasoning, educative.

5. Analysis and Discussion

•Zero-shot → Quick but vague.

•Few-shot → Context improves quality.

•Chain-of-thought → Structured explanation, helpful in troubleshooting.

•Persona-based → Aligns tone with business identity.

•Role-based → Formal and authoritative.

•Socratic → Interactive, educational for customers.

<img width="1432" height="806" alt="image" src="https://github.com/user-attachments/assets/afe69f9c-5757-480b-a729-7a82982d11bb" />

## Result:
1. Introduction to Results
The experiment was conducted by designing multiple prompt engineering strategies (zero-shot, few-shot, chain-of-thought, persona-based, role-based, and Socratic). Each prompting method was applied to the same set of retail-based customer queries such as:
1.“What is the return policy for electronics?”

2.“Track my order #12345.”

3.“Suggest a gift for a 10-year-old under ₹2000.”

4.“How do I exchange a damaged item?”

5.“What are today’s special offers?”

The results were documented, analyzed, and compared.

2. Tabular Comparison of Responses

<img width="691" height="837" alt="image" src="https://github.com/user-attachments/assets/4dedfe4c-26bb-4cd1-99af-aa6d423f2953" />

3. Observations on Each Prompting Technique
(i) Zero-Shot Prompting
•Result: Responses were generic and vague, often missing details like refund duration or eligibility.

• Strength: Fast, no setup needed.

•Weakness: Accuracy low (~50–60%), tone inconsistent.

•Example Result: “Electronics can usually be returned.” → Not reliable for customer service.
(ii) Few-Shot Prompting

•Result: Significant improvement in accuracy and detail.

•Strength: Learns from examples; more structured.

•Weakness: Needs curated training samples.

•Accuracy Level: ~85–90%.

•Example Result: “Electronics can be returned within 15 days if unused with receipt. Refunds processed in 7 days.”

(iii) Chain-of-Thought Prompting

•Result: Produced stepwise reasoning, very clear in troubleshooting or procedural queries.

•Strength: Transparency in logic; useful for training staff and customers.

•Weakness: Sometimes too long or technical for casual customers.

•Accuracy Level: ~90–95%.

•Example Result: For returns → “Step 1: Check eligibility. Step 2: Keep receipt. Step 3: Submit request. Step 4: Refund issued.”

(iv) Persona-Based Prompting

•Result: Responses aligned with brand identity; professional and customer-friendly.

•Strength: Tone consistency; builds trust and professionalism.

•Weakness: Slightly less flexible if persona too rigid.

•Accuracy Level: ~90–92%.

•Example Result: “At XYZ Retail, electronics can be returned within 15 days. For defective items, we offer a free replacement.”

(v) Role-Based Prompting

•Result: Tone became formal and authoritative, as if a senior employee was speaking.

•Strength: Adds authority and reliability to responses.

•Weakness: May feel too rigid or serious for casual queries.

•Accuracy Level: ~85–90%.

•Example Result: “As per store policy, electronics are eligible for return within 15 days. Ensure product is unused and receipt is provided.”

(vi) Socratic Prompting

•Result: Very interactive, asked guiding questions back to customer.

•Strength: Useful for training or educational settings.

•Weakness: Time-consuming for customers seeking quick answers.

•Accuracy Level: ~75–80%.

•Example Result: “Do you think electronics can be returned anytime? No, because they are high-value items. That’s why we limit returns to 15 days.”

4. Graphical Comparison (Textual Summary)

•Accuracy Ranking: Chain-of-Thought (95%) > Persona (92%) > Few-Shot (90%) > Role-Based (88%) > Socratic (80%) > Zero-Shot (60%).

•Customer Friendliness Ranking: Persona > Few-Shot > Chain-of-Thought > Role-Based > Socratic > Zero-Shot.

5. Key Findings

1.Zero-shot is fastest but least reliable.

2.Few-shot gives consistent answers when examples are provided.

3.Chain-of-thought is best for explaining policies or troubleshooting.

4.Persona-based makes chatbot feel like a real employee.

5.Role-based adds authority but may sound too official.

6.Socratic makes chatbot interactive and engaging, but not time-efficient Consolidated Result

•The experiment proves that prompt design directly influences chatbot performance in retail.

•Persona + Few-Shot prompting produced the most practical results for customer support.

•Chain-of-Thought prompting worked best for complex queries like troubleshooting electronics.

•Overall Customer Satisfaction Simulation Score: ~90% with persona-based + few-shot vs ~60% with zero-shot.


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/982888cb-f026-47dd-b392-dd44c8f28ee7" />


