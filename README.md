This repository is made to test "llm-rubric" in promptfoo.

SETUP:

To setup promptfoo in your local machine, follow the steps given on this page:
https://www.promptfoo.dev/docs/installation/

To run the code, use the following command:
> promptfoo eval

To see the results report in the browser, run the following command:
> promptfoo view

Please note that this required download Node.js from here:
https://nodejs.org/en/download

The promptfoo commands shared worked fine in "cmd", though they had some restrictions when running in VS Code. In the current state, these restrictions were not addressed.

TEST DESCRIPTION:
For this workflow, we use the LLM as a eveluator.

I ask it to check the generated test code for:
1. It uses the right qualification method (calling this Rule 1).
2. It uses the correct syntax for the valid qualification method in use (calling this Rule 2).