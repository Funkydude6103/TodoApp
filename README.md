<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #007acc;
            padding: 20px;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        .container {
            max-width: 960px;
            margin: 40px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #007acc;
            border-bottom: 2px solid #007acc;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        p {
            line-height: 1.6;
        }
        .features, .guidelines, .deliverables, .usage {
            margin-bottom: 40px;
        }
        .features ul, .guidelines ul, .deliverables ul {
            list-style: none;
            padding: 0;
        }
        .features li, .guidelines li, .deliverables li {
            margin-bottom: 10px;
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .features li::before, .guidelines li::before, .deliverables li::before {
            content: "✔";
            color: #007acc;
            font-weight: bold;
            margin-right: 10px;
        }
        footer {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>To-Do List App</h1>
    <p>A basic To-Do List application with a splash screen, task management, and responsive UI.</p>
</header>

<div class="container">
    <section class="objective">
        <h2>Objective</h2>
        <p>The goal of this project is to build a basic To-Do List application where users can add, view, and manage their tasks. The app will feature a splash screen with animations, use fragments for task entry, and have a responsive user interface using ConstraintLayout.</p>
    </section>

    <section class="features">
        <h2>Features</h2>
        <ul>
            <li>Splash Screen with Translate and Scale Animations</li>
            <li>Main To-Do List Page with Add Task Button</li>
            <li>Task Input Fragment with Save Functionality</li>
            <li>Responsive UI Using ConstraintLayout</li>
        </ul>
    </section>

    <section class="guidelines">
        <h2>Development Guidelines</h2>
        <ul>
            <li>All strings must be stored in the “strings.xml” file.</li>
            <li>All dimensions must be defined in “dimens.xml”.</li>
            <li>All colors should be declared in “colors.xml”.</li>
            <li>Layouts must be responsive, using ConstraintLayout for both portrait and landscape modes.</li>
            <li>Consistency across design, colors, fonts, and spacing.</li>
        </ul>
    </section>

    <section class="deliverables">
        <h2>Deliverables</h2>
        <ul>
            <li>XML layouts for each screen and fragment.</li>
            <li>Java code for splash screen animations, fragment navigation, and task management.</li>
            <li>Log fragment lifecycle events (onCreate, onStart, onResume) to the console.</li>
            <li>Fully responsive design for all screens.</li>
        </ul>
    </section>

    <section class="usage">
        <h2>How to Use the Application</h2>
        <p>After installing and launching the app, you'll first see the splash screen with animations. Once the animation completes, you will be taken to the To-Do list screen where you can:</p>
        <ul>
            <li>Add new tasks by tapping the '+' floating action button.</li>
            <li>Input task details (name, description) in the task input fragment.</li>
            <li>Save the task and return to the main list where the new task will appear.</li>
        </ul>
    </section>
</div>

<footer>
    <p>Made with ❤ by Tayyab Anees</p>
</footer>

</body>
</html>
