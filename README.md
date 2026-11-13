# 📍 CampusFind

**A Lost & Found app for university campus** | Android (Java) | Material Design 3 | SQLite

## **About the App**

CampusFind helps students **report lost items**, **post found items** and **find nearby items** on campus using GPS location.

## **Features**

- **Register and Login** with email and password
- **Home** screen with list of all lost and found items
- **Search and Filter** items (All / Lost / Found)
- **Report Item** with title, category, place, contact and date
- **Current Location** tagging using GPS
- **Nearby** tab showing items sorted by distance
- **Item Details** with Open in Maps and Mark as Returned
- **Profile** screen with Logout
- **Secure passwords** using salted SHA-256 hashing

## **Tech Stack**

- **Language:** Java 17
- **UI:** Material Design 3, Fragments, RecyclerView
- **Database:** SQLite (local)
- **IDE:** Android Studio (Gradle)
- **SDK:** Min 26, Target 34

## **Project Files**

- **LoginActivity.java** – login screen
- **RegisterActivity.java** – sign up screen
- **MainActivity.java** – bottom navigation
- **HomeFragment.java** – item list, search, filters
- **NearbyFragment.java** – items sorted by distance
- **ReportFragment.java** – report lost or found item
- **ProfileFragment.java** – profile and logout
- **LocationFragment.java** – location and permissions
- **DetailsActivity.java** – item details
- **DbHelper.java** – SQLite database and authentication
- **Session.java** – login session
- **ItemAdapter.java / Item.java / Util.java / Config.java** – adapter, model, helpers, settings
- **res/** – layouts, icons, themes
## **How to Run**

1. Open **Android Studio** and select **File > Open**.
2. Choose the folder containing `settings.gradle`.
3. Wait for **Gradle sync** to finish.
4. Select an emulator or phone and press **Run**.
5. Register a new account to enter the app.

**Emulator location (for Nearby tab):** **... > Location**, enter `31.38955, 74.24070` and click **Send location**.
