# PawCare Nepal

PawCare Nepal is a cross-platform Flutter mobile application designed to help pet owners manage their pets' health and daily care in Nepal. Users can manage pet profiles, track vaccinations, monitor medicines, schedule vet appointments, and keep all important pet-care information in one place.

Built for **ST6002CEM: Mobile Application Development** at Softwarica College of IT and E-Commerce, Coventry University.

## Why PawCare Nepal?

Pet care management in Nepal is still mostly handled through paper records, phone calls, and personal reminders. This creates challenges for both pet owners and their pets:

| For pet owners | For pets |
|------------|------------|
| Difficulty keeping track of health records | Missed vaccinations and health checkups |
| Forgetting medicine schedules | Irregular medication routines |
| Difficulty remembering vet appointments | Delayed medical attention |
| Pet information stored in different places | Inconsistent daily care |
| No single place to manage pet details | Important health information can be lost |

**PawCare Nepal exists to solve these problems.**

It brings pet profiles, health records, vaccination tracking, medicine reminders, vet appointments, and daily care management into one mobile application, helping pet owners take better care of their pets.

### Why a mobile app?

Most people use smartphones for their daily activities. A mobile application makes it easier for pet owners to access their pets' information, check health records, manage appointments, and receive important reminders anytime.

### Why Flutter?

Flutter allows developers to build cross-platform applications using a single codebase. It supports Android development now, with iOS possible later, making it suitable for a student project without developing two separate native applications.

### Why MVVM?

MVVM separates the application into three main parts: View, ViewModel, and Model. This keeps the user interface, application logic, and data management separate. It makes features such as pet profiles, vaccination records, medicine schedules, and appointments easier to develop, test, and maintain.

### Why health tracking and reminders in the same app?

Managing pet health requires regular attention. Pet owners need to remember vaccination dates, medicine schedules, and vet appointments. Keeping these features together helps owners stay organised and ensures important pet-care activities are not easily forgotten.

## Features

### Pet Owner
- Register and log in securely
- Create and manage pet profiles
- Add pet details such as name, age, breed, and profile photo
- Track pet health records
- Manage vaccination records and upcoming vaccination dates
- Add and monitor medicine schedules
- Receive medicine and vaccination reminders
- Schedule and manage vet appointments
- View pet-care information in one place
- Manage profile and settings

### Pet Health Management
- Store important medical information
- Track vaccination history
- Monitor ongoing medications
- Keep records of vet visits
- View upcoming health-related activities

### Stretch goals
- Push notifications for medicine and vaccination reminders
- Health reports and activity history
- Multiple pet management under one account

## Architecture

PawCare Nepal follows the **MVVM** pattern:

| Layer | Responsibility |
|-------|----------------|
| **Model** | Data and repositories for users, pets, health records, vaccinations, medicines, and appointments |
| **View** | Flutter screens and widgets for pet owners and pet-care management |
| **ViewModel** | UI state and application logic using Provider and ChangeNotifier |

## Tech stack

- Flutter / Dart
- Provider (state management)
- REST API / Firebase (as configured)
- Figma (UI prototypes)
- Git and GitHub (version control)

## Getting started

```bash
git clone https://github.com/YOUR_USERNAME/PawCare_Nepal_Mobile_App.git
cd PawCare_Nepal_Mobile_App
flutter pub get
flutter run
```

## Scope notes

**Included**
- Pet owner registration and login
- Pet profile management
- Health and vaccination tracking
- Medicine schedule management
- Vet appointment management
- Sample / demo pet data

**Not included**
- Live video consultations with veterinarians
- Online medicine purchasing
- Real-time veterinary emergency services
- Advanced AI-based disease diagnosis

## Author

**Prajita Shrestha**  
**Student ID:** 240099  
**Module:** ST6002CEM – Mobile Application Development  
**Institution:** Softwarica College of IT and E-Commerce, Coventry University.
