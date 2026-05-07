# Practice Assessment for Exam GH-300: GitHub Copilot

1. What is the purpose of code refactoring?

    - (A) To alter the external behavior or functionality of the code.
    - (B) To improve the internal structure of the code without altering its external behavior or functionality.
    - (C) To add new features or enhancements to the code.
    - (D) To optimize the code for better performance.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Refactoring enhances the internal structure while maintaining the same external behavior.</strong><br>
    Refactoring improves readability, maintainability, and design without changing external behavior, making future changes safer and easier.
    </details>

2. What is the primary purpose of project documentation in software development?

    - (A) To provide a detailed codebase for developers to use.
    - (B) To generate a high-level overview for the end-users of the software.
    - (C) To provide essential information for understanding the project's scope and purpose.
    - (D) To create a timeline of the project's development history.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Project documentation outlines the scope, purpose, and requirements, aiding understanding and collaboration.</strong><br>
    Good project documentation helps team members and stakeholders understand goals, requirements, constraints, and how to contribute effectively.
    </details>

3. What is the purpose of generating inline code documentation in software development?

    - (A) To make the code more complex and challenging for other developers.
    - (B) To create a more readable and maintainable codebase that's easier for other developers to understand and work with.
    - (C) To increase the size of the codebase.
    - (D) To showcase the developer's coding skills.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Inline code documentation enhances readability and maintainability.</strong><br>
    Inline comments and docstrings help other developers (and your future self) understand intent, inputs, outputs, and edge cases.
    </details>

4. What types of code conversions can be completed using GitHub Copilot?

    - (A) Convert an entire code file, a function, or a code snippet to an image.
    - (B) Convert an entire code file, a function, or a code snippet to another programming language.
    - (C) Convert a programming language to a human language.
    - (D) Convert compiled code back to source code.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — GitHub Copilot can assist in converting code between programming languages.</strong><br>
    Copilot can help translate snippets, functions, or files between languages to speed cross-language development.
    </details>

5. How does GitHub Copilot determine the code completion suggestions it provides?

    - (A) Based on the context of code in the editor.
    - (B) Based on the programming language used.
    - (C) Based on the length of the code written.
    - (D) Based on a random selection of popular coding patterns.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — GitHub Copilot analyzes the context of the code in the editor to provide suggestions.</strong><br>
    Copilot uses surrounding code, comments, and file context to produce relevant completions.
    </details>

6. How does Copilot use an organization's codebase and internal knowledge to enhance productivity and collaboration?

    - (A) By providing code suggestions based on open-source libraries only
    - (B) By tailoring coding assistance, answering questions, and suggesting code aligned with the organization's standards and best practices
    - (C) By suggesting code without considering the project context
    - (D) By randomly generating code snippets

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Copilot can leverage an organization's codebase and internal knowledge to provide tailored assistance.</strong><br>
    When configured, Copilot can use org-level context to suggest patterns and styles consistent with internal standards.
    </details>

7. How does GitHub Copilot work?

    - (A) GitHub Copilot uses prompts and natural language text that you type to provide coding suggestions.
    - (B) GitHub Copilot uses lights that you type, and it provides suggestions based on what you type.
    - (C) GitHub Copilot uses radio language that you type, and it provides suggestions based on what you type.
    - (D) GitHub Copilot uses binary code input to generate suggestions.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — GitHub Copilot uses prompts and natural language text that you type to provide coding suggestions.</strong><br>
    Copilot translates natural language and code context into suggested completions and snippets.
    </details>

8. How does GitHub Copilot learn from your prompts?

    - (A) It only relies on its pre-existing training data.
    - (B) It utilizes various approaches including zero-shot, one-shot, and few-shot learning.
    - (C) It requires extensive manual training on specific tasks.
    - (D) It cannot learn and adapt based on user interactions.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Copilot utilizes approaches like zero-shot, one-shot, and few-shot learning to adapt to prompts.</strong><br>
    These techniques help the model generalize from examples and adapt to new tasks with minimal examples.
    </details>

9. Which of the following is NOT a step in the process of GitHub Copilot processing a user's prompt into a code suggestion?

    - (A) Statistical analysis and pattern recognition
    - (B) Secure prompt transmission and context gathering
    - (C) Content filtering to ensure safety and security
    - (D) Context analysis to understand the user's intent

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Statistical analysis and pattern recognition is not listed as a specific step in the described flow.</strong><br>
    The described processing flow highlights secure transmission, context gathering, filtering, and intent analysis.
    </details>

10. How does the Fill-in-the-Middle (FIM) technique enhance GitHub Copilot's code suggestions?

    - (A) By allowing Copilot to process larger code files more efficiently
    - (B) By providing Copilot with access to more training data
    - (C) By enabling Copilot to consider a wider context of code surrounding the cursor position
    - (D) By improving Copilot's ability to understand natural language prompts

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — FIM enables Copilot to consider a wider context of code surrounding the cursor.</strong><br>
    FIM helps the model fill gaps by analyzing surrounding code before and after the cursor position.
    </details>

11. In the outbound flow of GitHub Copilot, which of the following actions might occur after the code suggestion is generated?

    - (A) The suggestion is immediately integrated into the user's code
    - (B) The suggestion is presented to the user for review and acceptance
    - (C) The suggestion is sent to a third-party server for evaluation
    - (D) The suggestion is automatically deleted to protect user privacy

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — The suggestion is presented to the user for review and acceptance.</strong><br>
    Users always review and accept suggestions before they become part of the code.
    </details>

12. What happens when GitHub Copilot generates more than one code completion suggestion?

    - (A) It adds all of the suggestions to your code.
    - (B) It selects the most relevant suggestion automatically.
    - (C) It enables developers to review each suggestion by selecting the left or right arrows.
    - (D) It discards all but the first suggestion.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Developers can review each suggestion by selecting the left or right arrows.</strong><br>
    Copilot surfaces multiple options so developers can choose the one that best fits.
    </details>

13. What is the purpose of reviewing and correcting the output generated by GitHub Copilot Chat?

    - (A) To ensure that the AI is learning correctly.
    - (B) To ensure the accuracy and completeness of the generated explanations and documentation.
    - (C) To provide feedback to the AI for future improvements.
    - (D) To track the performance of the AI over time.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Review ensures the accuracy and completeness of generated explanations and documentation.</strong><br>
    Human oversight is essential as AI-generated content can contain errors or omissions.
    </details>

14. Identify which statement is valid and select the correct answer:

    - (A) A prompt, which is our output, is a collection of songs that tells our copilot what to generate.
    - (B) A prompt, which is our input, is a collection of instructions or guidelines that tell our copilot what to generate.
    - (C) A prompt, which is our document, is a collection of laptops that tells our Copilot what to generate.
    - (D) A prompt is a series of binary commands that control Copilot's behavior.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — A prompt is the input: instructions or guidelines that tell Copilot what to generate.</strong><br>
    Prompts provide the model with context, constraints, and desired outputs.
    </details>

15. What does the quality of the output from GitHub Copilot depend on?

    - (A) Your code editor.
    - (B) How well your extensions were installed.
    - (C) How well you crafted your prompt.
    - (D) The time of day you're coding.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — The quality depends on how well you crafted your prompt.</strong><br>
    Clear, specific prompts usually produce better, more relevant suggestions.
    </details>

16. What is the role of Large Language Models (LLMs) in GitHub Copilot?

    - (A) To manage user accounts and billing information
    - (B) To understand and analyze the user's code structure
    - (C) To generate context-aware code suggestions and respond to prompts
    - (D) To compile and execute the generated code within the IDE

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — LLMs generate context-aware code suggestions and respond to prompts.</strong><br>
    The LLM interprets prompts and context to produce helpful code completions and explanations.
    </details>

17. What percentage of developers said that GitHub Copilot helps them code faster?

    - (A) 70%
    - (B) 83%
    - (C) 65%
    - (D) 90%

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>D — 90% of developers said Copilot helps them code faster.</strong><br>
    This figure comes from GitHub's published user research and marketing materials.
    </details>

18. Is GitHub Copilot free?

    - (A) Yes, it's free for everyone.
    - (B) No, it's a service you can sign up for that's free for students to use but currently costs 10 dollars per month.
    - (C) It's not free, even if you're a student or a teacher.
    - (D) It's free for the first month, then requires a subscription.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — GitHub Copilot is free for students but generally requires a paid subscription (around $10/month for individual users).</strong><br>
    Pricing and promotions may change; check GitHub's official pricing page for current details.
    </details>

19. What are the supported integrated development environment extensions for GitHub Copilot?

    - (A) Visual Studio Code and Visual Studio.
    - (B) GitHub.com, Visual Studio Code, Visual Studio, Neovim, and JetBrains.
    - (C) Visual Studio Code, Visual Studio, Neovim, and JetBrains.
    - (D) Only Visual Studio Code.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Copilot supports extensions for Visual Studio Code, Visual Studio, Neovim, and JetBrains.</strong><br>
    GitHub.com integrations (Copilot on the web) also offer other features; check docs for details.
    </details>

20. What is the difference between GitHub Copilot Business and GitHub Copilot Enterprise?

    - (A) GitHub Copilot Enterprise has code completions, while GitHub Copilot Business does not.
    - (B) GitHub Copilot Enterprise has chat in IDE and mobile, while GitHub Copilot Business does not.
    - (C) GitHub Copilot Enterprise has an extra layer of personalization, with organization utilizing their own codebase to train GitHub Copilot.
    - (D) GitHub Copilot Enterprise has an extra layer of security, with IP indemnity and enterprise-grade security, safety, and privacy.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Enterprise provides extra personalization options using an organization's codebase.</strong><br>
    Enterprise plans often include additional security, governance, and deployment features for large organizations.
    </details>

21. After you enforced your GitHub Copilot for Business policy, where do you first navigate in order to enable Copilot for Business for all current and future users?

    - (A) Policies
    - (B) Your organizations in your profile dropdown menu
    - (C) Settings in your profile dropdown menu
    - (D) Selected teams/users

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Navigate to your organizations in your profile dropdown menu.</strong><br>
    From the organization settings you can enable Copilot for Business for members and teams.
    </details>

22. Which of these advanced features aren't available in GitHub Copilot Enterprise but were available in GitHub Copilot Business?

    - (A) Copilot Chat Customized to your Codebase
    - (B) Copilot Pull Request Summaries
    - (C) Copilot Documentation Search and Summaries using Docsets
    - (D) None of the above

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>D — None of the above; these advanced features are available in Enterprise as well.</strong><br>
    Enterprise includes personalization, summaries, and docset-based features depending on configuration.
    </details>

23. Describe the purpose and benefits of Copilot's pull request summaries in GitHub Copilot Enterprise.

    - (A) They aim to provide a detailed history of code changes in pull requests.
    - (B) They assist in automatically generating concise overviews of pull requests based on code changes, enhancing understanding and accelerating review processes.
    - (C) They track developers' activity within a pull request.
    - (D) They automatically merge pull requests without human intervention.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Pull request summaries generate concise overviews to speed reviews.</strong><br>
    Summaries highlight key changes and help reviewers focus on important diffs and potential issues.
    </details>

24. How can GitHub Copilot Chat assist in improving the modularity of a class?

    - (A) By suggesting potential refactoring updates based on the context of your codebase.
    - (B) By providing a detailed analysis of the class's dependencies.
    - (C) By automatically rewriting the entire class.
    - (D) By generating unit tests for each method in the class.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Copilot Chat can suggest refactoring updates based on context.</strong><br>
    The chat can propose ways to extract responsibilities, reduce coupling, and increase cohesion.
    </details>

25. How does GitHub Copilot Chat propose fixes for bugs in your code?

    - (A) By running automated tests and identifying the root cause.
    - (B) By suggesting code snippets and solutions based on the context of the error or issue.
    - (C) By comparing your code with a database of known bug patterns.
    - (D) By simulating various input scenarios to detect edge cases.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — It suggests code snippets and solutions based on the error context.</strong><br>
    Copilot Chat uses the code context and error messages to propose potential fixes and explanations.
    </details>

26. How can GitHub Copilot Chat assist when encountering an error in the code?

    - (A) It can explain the cause of the error and suggest ways to fix it.
    - (B) It can prevent errors from occurring in the first place.
    - (C) It can automatically fix the error without any user interaction.
    - (D) It can run a series of automated tests to isolate the error.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — It can explain the cause of the error and suggest fixes.</strong><br>
    The chat provides guidance and example patches that the developer can review and apply.
    </details>

27. How can GitHub Copilot Chat be used in the context of project documentation?

    - (A) To generate specific sections of the project documentation, such as the project overview, requirements, constraints, dependencies, and summary.
    - (B) To communicate with the project stakeholders and gather their requirements.
    - (C) To automatically write the entire codebase for the project.
    - (D) To create visual diagrams and charts for the documentation.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — It can generate sections like overview, requirements, and summaries.</strong><br>
    Copilot Chat speeds creating docs by expanding bullet points into full sections and suggesting structure.
    </details>

28. How can GitHub Copilot Chat help generate inline code documentation?

    - (A) By automatically writing the entire codebase.
    - (B) By generating inline code comments based on natural language prompts or commands.
    - (C) By providing real-time chat support with other developers.
    - (D) By creating separate documentation files for each code module.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — It can generate inline code comments from natural language prompts.</strong><br>
    Use the chat to request summaries or explanations to be inserted as comments or docstrings.
    </details>

29. How do you access GitHub Copilot's inline chat?

    - (A) Access the inline chat by clicking on the chat icon in the left sidebar of Visual Studio Code.
    - (B) Use Ctrl+i on Windows or Command+i on a Mac to open the inline chat.
    - (C) Access the inline chat by using Alt+i on Windows or Option+i on a Mac.
    - (D) Type "/chat" anywhere in your code to open the inline chat.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Use Ctrl+i on Windows or Command+i on a Mac to open the inline chat.</strong><br>
    Keyboard shortcuts provide quick access to inline chat features within the editor.
    </details>

30. What are slash commands used for in GitHub Copilot?

    - (A) Slash commands are used to format your codebase according to best practices.
    - (B) Slash commands are used to debug code and detect security vulnerabilities within your projects.
    - (C) Slash commands are shortcuts to quickly solve common development tasks within the chat or inline pane.
    - (D) Slash commands are used to switch between different programming languages.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Slash commands are shortcuts to quickly solve common development tasks.</strong><br>
    Examples include generating tests, refactoring, or creating summaries via short commands.
    </details>

31. What are the benefits of using agents like '@terminal' or '@workspace' when interacting with GitHub Copilot?

    - (A) Agents in Visual Studio Code help you ask questions within a specific context, allowing for more precise and relevant answers from GitHub Copilot.
    - (B) Agents help enforce a consistent code format based on best practices within Visual Studio Code for improved readability.
    - (C) Agents provide extra security features for detecting vulnerabilities and intrusions within Visual Studio Code projects.
    - (D) Agents automatically optimize your code for better performance.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Agents help you ask questions within a specific context for more precise answers.</strong><br>
    Contextual agents narrow scope to terminal outputs, workspace files, or other data sources.
    </details>

32. What are the benefits of using implicit prompts with slash commands in inline chat for fixing code issues with GitHub Copilot?

    - (A) Implicit prompts help enforce a consistent naming convention and syntax based on best practices within Visual Studio Code projects for improved readability.
    - (B) Implicit prompts help get better responses from GitHub Copilot without writing longer prompts, making it easier to interact and fix code issues.
    - (C) Implicit prompts help detect security vulnerabilities and potential malicious activities within Visual Studio Code projects for increased safety.
    - (D) Implicit prompts automatically refactor your code to follow design patterns.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Implicit prompts help get better responses without writing longer prompts.</strong><br>
    They provide succinct context that yields focused, actionable outputs.
    </details>

33. What is the importance of context and intent when developing prompts for GitHub Copilot Chat?

    - (A) They determine the color scheme used by GitHub Copilot Chat.
    - (B) They control the volume of the audio output from GitHub Copilot Chat.
    - (C) They specify the scope that GitHub Copilot should examine and the goal to be achieved.
    - (D) They influence the programming language used for code suggestions.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Context and intent specify the scope Copilot should examine and the goal to achieve.</strong><br>
    Clear context helps the model focus on relevant files and constraints.
    </details>

34. What is a recommended practice to improve the performance of GitHub Copilot Chat?

    - (A) Limiting the prompt to coding questions or tasks to enhance the model's output quality.
    - (B) Using Copilot Chat as a replacement for human programming.
    - (C) Ignoring secure coding and code review practices.
    - (D) Asking Copilot Chat to generate entire applications without any guidance.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Limit prompts to coding questions or tasks to improve output quality.</strong><br>
    Focused prompts reduce ambiguity and help the model produce accurate responses.
    </details>

35. What is the best way to provide context to GitHub Copilot for better code suggestions?

    - (A) By keeping all files closed in the editor.
    - (B) By using complex function names.
    - (C) By providing meaningful function names, specific function comments, and having related files open in the editor.
    - (D) By writing code without any comments or documentation.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Provide meaningful names, comments, and keep related files open.</strong><br>
    These practices give Copilot clear signals about intent and structure.
    </details>

36. How can a developer optimize their experience when interacting with GitHub Copilot via chat?

    - (A) By being vague about the inputs, outputs, APIs, or frameworks they want to use.
    - (B) By using chat participants, slash commands, chat variables, and being specific in your prompts.
    - (C) By asking Copilot to perform large tasks at once.
    - (D) By avoiding the use of code snippets in prompts.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Use chat participants, slash commands, chat variables, and be specific in prompts.</strong><br>
    Structured prompts and tools yield more usable results.
    </details>

37. Which of the following is NOT a principle of effective prompt engineering for GitHub Copilot?

    - (A) Clarity - Focus on a single, well-defined task.
    - (B) Verbosity - Provide extensive and detailed descriptions.
    - (C) Specificity - Use clear and explicit instructions.
    - (D) Surround - Utilize descriptive filenames and keep related files open.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Verbosity is not a recommended principle; prefer clarity and specificity.</strong><br>
    Long, unfocused prompts can introduce ambiguity and reduce suggestion quality.
    </details>

38. What is the role of GitHub Copilot Chat in generating unit test cases?

    - (A) It manually writes all the test cases for the user.
    - (B) It only suggests possible input parameters and expected output values.
    - (C) It helps generate code snippets for test cases based on the code specified by the user, suggests possible input parameters, expected output values, and assertions, and can help identify edge cases and boundary conditions.
    - (D) It automatically runs all unit tests and reports the results.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — It helps generate code snippets for test cases and suggests inputs, outputs, and assertions.</strong><br>
    Copilot speeds test creation, suggests edge cases, and helps document expected behavior.
    </details>

39. What is the purpose of the Test Explorer in Visual Studio Code?

    - (A) To write new code snippets for unit tests.
    - (B) To run and debug unit tests, view the results of test runs, and manage test cases in the workspace.
    - (C) To generate test cases based on the code context.
    - (D) To automatically fix failing tests.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — The Test Explorer runs and debugs tests, shows results, and manages test cases.</strong><br>
    It provides a centralized interface for test discovery and execution.
    </details>

40. What is the significance of the Arrange, Act, and Assert sections in unit tests?

    - (A) They are used to organize the code in the main application.
    - (B) They are used to structure unit tests into setup (Arrange), execution (Act), and verification (Assert) phases.
    - (C) They are used to compile and run the unit tests.
    - (D) They are used to generate documentation for the tests.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — They structure tests into Arrange, Act, and Assert phases for clarity and maintainability.</strong><br>
    This pattern improves readability and ensures tests are well-structured.
    </details>

41. What does GitHub Copilot provide when creating unit tests for specific conditions?

    - (A) It provides a user interface for manually writing tests.
    - (B) It automatically runs the tests and provides the results.
    - (C) It suggests completions and generates tests based on the code context.
    - (D) It creates a full test suite without any user input.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Copilot suggests completions and generates tests based on context.</strong><br>
    Developers review and refine suggested tests before running them.
    </details>

42. What is the benefit of using GitHub Copilot for generating unit tests?

    - (A) It reduces the need for manual testing.
    - (B) It can suggest a range of unit tests based on the code context, saving development time.
    - (C) It automatically fixes bugs in the code.
    - (D) It guarantees 100% code coverage.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — It suggests a range of unit tests based on code context, saving time.</strong><br>
    Suggested tests provide a starting point that developers can expand and validate.
    </details>

43. What is the purpose of generating assertions to ensure that function input parameters are valid?

    - (A) To enhance the performance of the function.
    - (B) To prevent invalid data from being processed by the function.
    - (C) To check if the function returns the expected output.
    - (D) To document the function's expected inputs.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Assertions prevent invalid data from being processed by the function.</strong><br>
    Validations catch incorrect inputs early, improving reliability and safety.
    </details>

44. What factors can be considered when working on code quality improvements?

    - (A) The number of lines of code in the program.
    - (B) The time required to write code.
    - (C) Readability, complexity, modularity, reusability, testability, extensibility, reliability, performance, security, scalability, usability, and portability.
    - (D) The number of developers working on the project.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — Consider readability, complexity, modularity, reusability, testability, and more.</strong><br>
    A holistic view of quality covers maintainability, performance, security, and user needs.
    </details>

45. What does code reliability refer to in software development?

    - (A) The use of modern CPU architectures by parallelizing tasks and performing I/O operations asynchronously.
    - (B) The likelihood that software will function correctly under specific conditions and for a certain period of time.
    - (C) The efficiency of a program or application.
    - (D) The ability of the code to handle large amounts of data.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Code reliability is the likelihood software functions correctly under given conditions for a period of time.</strong><br>
    Reliability metrics help teams measure stability and failure rates.
    </details>

46. What is one way to improve code reliability?

    - (A) By optimizing algorithms and data structures for the task at hand.
    - (B) By identifying potential issues in the code to prevent bugs and errors from occurring.
    - (C) By minimizing disk and network I/O operations or performing them asynchronously.
    - (D) By using the latest programming language features and syntax.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Identify potential issues to prevent bugs and errors.</strong><br>
    Techniques include code review, static analysis, and targeted testing.
    </details>

47. What is the effect of maintaining a high quality bar in your code when using GitHub Copilot?

    - (A) Copilot latches on to your code to generate suggestions that follow the existing pattern.
    - (B) It confuses Copilot and leads to irrelevant suggestions.
    - (C) It slows down the suggestion process.
    - (D) It causes Copilot to ignore your existing code structure.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — High-quality code helps Copilot generate suggestions that follow existing patterns.</strong><br>
    Consistent, well-structured code yields more accurate completions.
    </details>

48. What are some ways to improve exception handling in code to make it more secure?

    - (A) Revealing sensitive information in exceptions, catching general exceptions only, and swallowing exceptions.
    - (B) Catch the most specific exceptions possible, avoid revealing sensitive information in exceptions, and avoid swallowing exceptions.
    - (C) Exposing detailed error information, catching only specific exceptions, and not rethrowing exceptions.
    - (D) Using try-catch blocks for every line of code and logging all exceptions to a public server.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Catch specific exceptions, avoid revealing sensitive info, and don't swallow exceptions.</strong><br>
    Proper handling preserves security and makes debugging easier without leaking secrets.
    </details>

49. What is the primary purpose of content filtering in GitHub Copilot?

    - (A) To prioritize speed and efficiency in code generation
    - (B) To suggest code that aligns with the latest coding trends
    - (C) To eliminate irrelevant or outdated information
    - (D) To prevent the generation of malicious or harmful code

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>D — The primary purpose is to prevent the generation of malicious or harmful code.</strong><br>
    Content filtering reduces security risks by blocking dangerous suggestions.
    </details>

50. What is the primary purpose of the toxicity filter in GitHub Copilot?

    - (A) To ensure code suggestions are syntactically correct
    - (B) To prevent the generation of code that violates intellectual property rights
    - (C) To eliminate harmful or offensive content in code suggestions
    - (D) To suggest code that adheres to specific coding standards

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — The toxicity filter eliminates harmful or offensive content in suggestions.</strong><br>
    This promotes respectful and inclusive outputs.
    </details>

51. How can GitHub Copilot Chat help generate explanations for unfamiliar code?

    - (A) By rewriting the code in a simpler language.
    - (B) By generating natural language descriptions of the code's functionality and purpose.
    - (C) By removing unnecessary parts of the code.
    - (D) By providing links to external documentation for similar code structures.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — It generates natural language descriptions of functionality and purpose.</strong><br>
    These explanations help developers quickly understand unfamiliar sections.
    </details>

52. What is ghost text in GitHub Copilot?

    - (A) Ghost text in GitHub Copilot are suggestions that appear in your text editor as you type.
    - (B) Ghost text in GitHub Copilot are options used when typing to provide suggestions.
    - (C) Ghost text in GitHub Copilot involves using prompts and natural language questions within your code or documentation.
    - (D) Ghost text in GitHub Copilot is a feature that automatically deletes unused code.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Ghost text are suggestions that appear in your editor as you type.</strong><br>
    Ghost text gives inline completions that can be accepted or ignored.
    </details>

53. What functionality isn't supported in GitHub Copilot for Individuals?

    - (A) VPN Proxy support via self-signed certificates
    - (B) Offers multi-line function suggestions
    - (C) Editor integration
    - (D) Blocks suggestions matching public code

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — VPN Proxy support via self-signed certificates is not supported for Individuals.</strong><br>
    Other capabilities like multi-line suggestions and editor integrations are supported.
    </details>

54. How can you accept GitHub Copilot's suggestions?

    - (A) Press the Tab key.
    - (B) Press the F1 key.
    - (C) Press the F4 key.
    - (D) Press the Enter key.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Press the Tab key to accept suggestions.</strong><br>
    The Tab key inserts the highlighted suggestion into your code.
    </details>

55. How can organizations manage and utilize docsets within Copilot Enterprise to tailor code suggestions and improve development workflows?

    - (A) By using docsets to create custom collections of internal code and documentation.
    - (B) By using docsets to automatically generate code snippets.
    - (C) By using docsets to track developers' activity within a project.
    - (D) By using docsets to enforce coding standards.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>A — Use docsets to create custom collections of internal code and documentation.</strong><br>
    Docsets enable Copilot to provide more relevant suggestions based on internal knowledge and docs.
    </details>

56. What is the purpose of using chat participants, slash commands, and chat variables in GitHub Copilot Chat?

    - (A) They limit the scope of the AI's responses.
    - (B) They add complexity to the chat interface.
    - (C) They help GitHub Copilot Chat understand the context and intent of the question.
    - (D) They allow users to customize the appearance of the chat interface.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>C — They help Copilot Chat understand context and intent.</strong><br>
    These features let you specify roles, variables, and shortcuts to guide responses.
    </details>

57. What are the two ways to generate code line completions using GitHub Copilot?

    - (A) Generate completions from a code line and from a code file.
    - (B) Generate completions from a comment and from a code line.
    - (C) Generate completions from a comment and from a prompt.
    - (D) Generate completions from a function name and from a variable name.

    <details>
    <summary><strong>Check your answer:</strong></summary>
    <strong>B — Generate completions from a comment and from a code line.</strong><br>
    Comments provide natural language intent while code lines provide immediate context for completions.
    </details>
