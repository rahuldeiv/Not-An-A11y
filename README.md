# Not-An-A11y
Open Science Repo for Not an A11y: How Android's Accessibility Framework Exposes Mobile AI Agents to Indirect Prompt Injection

Credentials, device identifiers, and potentially sensitive information are removed or redacted from all published traces and artifacts.

Released materials are sanitized and intended to support controlled reproduction and defensive research. 

1. Modified main.py & agent.py used at mobile-use\minitap\mobile_use\main.py and mobile-use\minitap\mobile_use\sdk\agent.py to improve logging. No other changes were made to Mobile_Use source code other than cosmetic modifications.
2. PaperReviwer is the controlled Android Application used for Attack A4.
3. Runtime Attack Injections contains variations of injections used for A1, A2 and A3, used across framework and configurations.
4. Logs provided under "Framework - Model".pdf.
5. Hardware, device, framework, and LLM configurations used in the evaluation can be found under Experiment_Environment_and_Config.pdf.
6. Representative Payload and Benign Tasks (a summary) can be found under Benign_task_and_representative_payload.pdf.
7. And finally, Experiments.xlsx contains all the trials, scores, metrics and data analysis.
