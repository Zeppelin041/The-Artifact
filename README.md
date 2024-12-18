# The-Artifact
Portfolio

1. Briefly summarize the requirements and goals of the application you developed. What user needs was this application designed to address?
The goal of this application was to develop a course registration system that allows students to register for courses interactively. It needed to enforce specific business rules, such as limiting total credit hours to nine and preventing duplicate course registration. The application was designed to meet the need for a straightforward, user-friendly interface for selecting courses, tracking registrations, and ensuring accurate credit hour totals.

2. What did you do particularly well in developing this application?
I excelled at integrating validation logic and creating a user-centered design. This included clear feedback messages for user errors and successes, ensuring that users always understood the system's status. The use of intuitive labels, list displays, and total credit hour tracking contributed to an engaging and efficient user experience.

3. Compare and contrast the Console and WPF application designs. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The Console application relied on text-based input and output, making it less visual and harder to navigate. In contrast, the WPF application introduced a graphical interface with ComboBoxes, Buttons, ListBoxes, and Labels to enhance usability. Features like dropdown course selection and real-time feedback via labels improved the user experience. The design was successful because it minimized errors, provided immediate validation, and presented information in a clean, organized layout.

4. How did you approach the process of debugging and coding your application? What techniques or strategies did you use? How could you use those techniques or strategies in the future?
I followed a systematic approach to debugging by testing each feature incrementally. For example, after implementing the credit limit check, I verified it before moving on to duplicate registration validation. Using meaningful variable names and modular functions like UpdateUI simplified debugging. These strategies—breaking down problems, isolating changes, and testing thoroughly—are applicable to any future software development project.

5. Where did you have to be innovative to overcome a challenge in the full application development process?
The primary challenge was dynamically updating the UI to reflect user actions while maintaining data integrity. I had to innovate by combining back-end logic (tracking registered courses and credit hours) with front-end elements (updating ListBox and TextBox values). This required thoughtful synchronization between code and design to ensure the application responded accurately to user inputs.

