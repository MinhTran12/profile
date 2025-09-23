# Cultivating Green Thumbs

We designed Plant Buddy: a learning application for botanic enthusiasts to learn plant care. The app guides users through plant care projects, tracks progress, and offers adaptive feedback. Recommendations are based on the user's knowledge and environment, suggesting beginner-friendly plants for novices. Users receive information on plant care, use self-reports and sensors for progress tracking, and eventually unlock more challenging plants as they gain knowledge. The system combines user observations with sensor data for effective learning and plant nurturing.

# Domain's Pedagogical Model

The proposed system focuses on horticultural knowledge, encompassing declarative facts and procedural skills for plant care. It divides this knowledge into five main components that can be divided into smaller sub-components:

![Plant care illustration](images/green-thumbs/knowledge-components.png)

# User Model and System Adaptation

The user model employs an overlay approach, assigning scores to skills and sub-skills related to plant care. Uncertainty is managed through user self-reports, environmental changes, and open-ended success criteria, with probabilities calculated based on user scores. Sensors provide data to validate user reports and offer guidance. The system tracks skill scores for individual plant projects and reports overall plant care skill scores to the user.

The adaptive plant care system operates on three levels of adaptation:

- It assesses the user's current knowledge level through quizzes and self-reports, as well as providing adaptive feedback to help with their current plant project;
- It conforms to the user's goals, allowing them the choice of picking more challenging plants based on past projects;
- It recognizes user's attributes, such as location and environmental factors, influencing plant species suggestions.

# Application UX/UI Design

To overcome the cold-start problem (the initial difficulty of onboarding new users with respect to their knowledge of horticulture specifically), the system employs an extensive onboarding process for new users, gathering information about their goals, prior experience, and knowledge by using a test, ensuring a personalized learning experience.

![onboarding-ui](images/green-thumbs/onboarding.png)

The instructional model for the plant care system combines the systematic knowledge representation of cognitivism and the hands-on experience of constructivism.

![application-userflow](images/green-thumbs/app-userflow.png)

The following are the main features of the app after onboarding:

- **Personalized recommendations**: After an intake quiz, the system suggests plants suitable for the user’s knowledge level and environment (e.g., climate, light).

- **Adaptive learning**: The system adjusts to user’s knowledge (via quizzes & feedback), goals (novice vs. advanced growth projects), and attributes (environmental conditions like humidity, light).

- **Learning materials**: Organized around plant needs (light, water, soil, nutrients, temperature, health diagnostics). Difficulty increases as the user progresses.

- **User model**: Tracks skills (watering, soil/composting, lighting, temperature, health diagnostics) with scores (0–100). Feedback comes from both sensors and self-reports.
