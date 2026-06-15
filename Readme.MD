# SmartSpend - Personal Budget Tracker

## Project Overview
SmartSpend is a comprehensive personal finance management application built with Kotlin and Android Studio. It follows modern Android development practices, utilizing the MVVM architecture and RoomDB for local data persistence. The app empowers users to track expenses, set budget goals, visualize spending habits through interactive charts, and stay motivated through a gamified achievement system.

## Key Features
- **User Authentication**: Secure login and registration.
- **Expense Management**: Add expenses with descriptions, categories, and receipt photo attachments.
- **Budget Goals**: Set minimum and maximum monthly spending goals.
- **Interactive Visualizations**: View spending distribution by category using MPAndroidChart.
- **Goal Progress Dashboard**: Real-time tracking of monthly spending against goals with visual progress bars.
- **Gamification System**: Earn badges (e.g., "Budget Master", "Savings Champion") for healthy financial habits.
- **Savings Challenges**: Engage in weekly and monthly challenges to boost savings.
- **Smart Budget Tips**: Receive personalized financial advice based on spending patterns.

## Architecture
The project is built using the **MVVM (Model-View-ViewModel)** architectural pattern:
- **Model**: RoomDB entities and DAOs handling data persistence.
- **View**: Fragments and Activities utilizing ViewBinding for UI interactions.
- **ViewModel**: Manages UI-related data and business logic, communicating with the Repository.
- **Repository**: Single source of truth for data operations, abstracting the data sources from the rest of the app.

## Database Design (RoomDB)
- **User**: Stores user credentials.
- **Category**: Custom spending categories.
- **Expense**: Detailed records of all transactions.
- **BudgetGoal**: Monthly spending limits and targets.
- **Badge**: Achievement system records.
- **SavingsChallenge**: Progress tracking for savings goals.

## CI/CD and DevOps
This project uses **GitHub Actions** for continuous integration:
- **Android Build Workflow**: Automatically builds the APK on every push.
- **Unit Testing Workflow**: Runs JUnit tests to ensure code reliability and prevent regressions.

## Installation Steps
1. Clone the repository: `git clone https://github.com/yourusername/SmartSpend.git`
2. Open the project in **Android Studio Hedgehog** (or later).
3. Ensure you have **JDK 17** configured.
4. Sync Project with Gradle Files.
5. Run the app on an emulator or physical device (Min SDK: 24).

## Custom Features
1. **Savings Challenge System**: A dedicated module where users can commit to specific saving targets, earning reward points upon completion.
2. **Smart Budget Tips**: An analysis engine that evaluates spending vs. goals and provides actionable advice to help users stay within budget.

## Video Demonstration
[Link to Video Demo] (Replace with actual link)

## Screenshots
*(Insert screenshots here in the final submission)*
