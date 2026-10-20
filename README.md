# GoalTrack – Mobile Application Project

## Project Overview and Goals

GoalTrack is an Android mobile application designed to help users track their daily weight and work toward a personal goal weight. The primary goal is to provide a convenient way for users to create an account, record weight entries, review their progress, and stay motivated. The application addresses the need for a simple, organized weight-tracking tool that allows users to maintain their information in one place.

## User Interface Design

The main screens include the login and account creation screen, dashboard, and data-entry screen. These screens support the user's ability to access the application, navigate its features, and enter weight information. The interface was designed with straightforward navigation and clearly identified actions in mind so users can understand how to use the application without unnecessary confusion. Organizing features into separate screens helps keep the interface focused and makes common tasks easier to complete.

## Development Approach

I developed GoalTrack using Android Studio and Java, with Android application components and SQLite database functionality supporting the app's features. I approached development incrementally by configuring the application structure, connecting activities, and working through navigation and functionality issues as they appeared. I also used error messages and Logcat to identify problems instead of making random code changes. These strategies can be applied to future projects by building applications in manageable stages, testing individual components, and addressing errors as early as possible.

## Testing and Results

I tested the application using the Android Emulator and verified that the app could launch and navigate between its screens. During development, I encountered crashes related to activity registration and navigation, including activities that needed to be declared in the Android manifest. Reviewing Logcat helped me identify the source of these errors and correct the configuration. Testing is important because an application that looks correct may still fail when users interact with it. This process taught me to test both individual features and the connections between application components.

## Challenges and Innovation

One of the main challenges was troubleshooting application crashes during navigation. Initially, the application would not open the intended login screen, and later, selecting the data-entry feature caused another crash. I investigated the errors, reviewed the Android manifest, and corrected the activity declarations to allow Android to locate the appropriate screens. This experience strengthened my understanding of how activities, manifests, and navigation work together. It also reinforced the importance of using debugging tools to identify the underlying cause of a problem.

## Demonstrated Skills and Strengths

The component in which I demonstrated the most growth was troubleshooting and connecting Android activities. By investigating crashes and correcting manifest configuration issues, I developed a better understanding of Android application structure and navigation. I also gained experience using Android Studio, Java, the Android Emulator, and Logcat. These skills will help me approach future software development projects more methodically, with greater attention to functionality, reliability, and user experience.

## Future Improvements

Future improvements could include more extensive testing of account creation and login, complete create/read/update/delete functionality for weight entries, clearer progress visualizations, and testing SMS notifications and runtime permissions if those features are included in the final implementation. Before publishing the application, I would verify that each feature works as intended, that user data is handled appropriately, and that the application behaves consistently across supported Android versions.
