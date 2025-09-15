🐾 **The Toe Bean Agenda**

**Project Overview and Purpose**
The Toe Bean Agenda is a simple, self-contained web application designed to help pet owners manage their pets' schedules and food inventory. Its primary purpose is to provide a single, easy-to-use place to track important tasks like feeding times, medicine doses, and vet appointments, while also keeping an eye on food stock levels. The application is built to be fully functional offline and uses local storage to save data directly in your browser.

**Features and Functionality**
Schedule Management: Easily add, edit, and delete schedules for your pets. Each schedule can include details like the pet's name, species, type of activity (Feeding, Medicine, etc.), and a detailed description.

Flexible Scheduling: Create one-time appointments with a specific date and time, or set up recurring schedules (daily, weekly, monthly) for consistent tasks.

Pet Photos: Personalize each schedule by uploading a photo of your pet, which will be displayed on the schedule card.

Food Inventory: Keep track of your pet's food with a dedicated inventory manager. You can add, update, or remove food items and track their stock status.

Browser Notifications: The app can send you pop-up notifications to remind you of upcoming scheduled events, so you never miss a beat. This requires your permission and works best when the app is open in a browser tab.

Data Export & Import: All of your data can be backed up by exporting it as a JSON file. You can also import this file at a later time to restore your schedules and inventory.

Search Functionality: Quickly find a specific schedule by searching for a pet's name, schedule type, or keywords in the details.

**Known Issues or Limitations**
Local Storage Only: Data is stored exclusively in your browser's local storage. This means your data is not synced across different devices or browsers. If you clear your browser's data, your schedules will be deleted unless you have exported them.

No Multi-User Support: The application is designed for a single user and does not have built-in functionality for sharing data or collaborating with others.

Static Images: Pet photos are stored as Base64 strings within the local data file, which can make the exported JSON file large if you add many photos.

**Future Enhancement Ideas**
Calendar View: Implement a visual calendar to show all schedules at a glance.

Sorting Options: Add the ability to sort schedules by pet name, date, or schedule type.

Multi-Device Sync: Transition to a cloud-based database (like Firestore) to enable real-time synchronization of data across multiple devices and users.

Customization: Allow users to create custom schedule types and set their own icons.

Reminders for Recurring Schedules: Currently, only one-time schedules send notifications. Future updates could enable notifications for recurring events as well.
