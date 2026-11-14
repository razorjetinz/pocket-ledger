# PocketLedger

A clean, offline-first personal money manager built with Flutter. Track income and expenses without creating an account or sending financial data to a server.

## Included in this first release
- Monthly overview with income, expenses and net balance.
- Add income and expense entries with category, date, account and optional note.
- Activity list with month navigation and swipe-to-delete.
- Category spending breakdown and simple monthly insights.
- Local SQLite storage; no account or network connection is required.
- INR (₹) as the initial display currency.

## Run locally
1. Install Flutter stable and Android Studio (or Xcode for iOS).
2. Clone this repository.
3. Run `flutter pub get`.
4. Run `flutter run`.

## Build Android
```bash
flutter build apk --release
```
APK output: `build/app/outputs/flutter-apk/app-release.apk`.

## Privacy and data
There is no sign-in, analytics, advertising SDK or cloud sync in this version. Transactions are stored in the app's local SQLite database. Encrypted backup, restore and app lock are not implemented yet. Uninstalling the app may remove local data; do not rely on this first release as the only copy of important financial records.

## Roadmap
- Budgets and recurring transactions.
- Account balances and transfers.
- CSV import/export and encrypted backup/restore.
- Detailed charts, search, filters and custom categories.
- App lock and multi-currency settings.

## License
MIT
