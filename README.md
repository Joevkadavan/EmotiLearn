# EmotiLearn
🚀 Algorithm: Dashboard Component Overview
Import Dependencies

Import React and useState to use React features and manage state.

Define Dashboard Component

Create a functional component called Dashboard that accepts user and navigateTo as props.

Initialize State

Use useState to define:

stats: Contains learning metrics like courses completed, hours watched, etc.

recentActivity: Stores a list of recent course activities (with progress and emotion data).

Render UI

Display a welcome message using user.name.

Show a summary grid with four key learning stats using the StatCard component.

Define StatCard Component

A reusable component that:

Accepts an icon, label, value, and delay.

Displays each stat inside a styled card.

Export Component

Export Dashboard as the default component so it can be used in other parts of the app.
