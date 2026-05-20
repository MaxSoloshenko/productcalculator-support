# ProductCalculator Support

ProductCalculator is a bookkeeping app for home bakers and small bakery owners. This page covers the most common questions.

## Where is my data stored?

Everything you enter is stored locally on your iPhone or iPad using Apple's SwiftData framework. Nothing is uploaded to any server. The app does not connect to the internet.

## How do I back up my data?

Open the app, tap the gear icon in the top-right corner of the dashboard to open Settings. Scroll to the **Data Tools** section and tap **Export CSV**. The app writes 10 CSV files into a folder called `BakeryCSVExport` inside your iPhone or iPad's Documents folder. You can find them in the Files app and copy them to iCloud Drive, AirDrop them to your computer, or email them to yourself.

## How do I move my data to a new device?

1. On the old device, export to CSV (see above).
2. Transfer the `BakeryCSVExport` folder to the new device via AirDrop, iCloud Drive, or any file-sharing method you prefer.
3. On the new device, install ProductCalculator, open Settings, and tap **Import CSV**. Select all 10 CSV files at once.

## What does "Clear All Data" do?

It permanently deletes every ingredient, packaging item, product, recipe, sale, order, expense, and price history record stored on your device. It also cancels any pending order reminders. Your business profile (name, currency, initials) is not affected. This action cannot be undone, so export a CSV backup first if you want to keep your data.

## Notifications are not arriving

1. Open **Settings** in the app and confirm **Schedule reminders** is on.
2. Open the iOS **Settings** app -> **Notifications** -> **ProductCalculator** and confirm notifications are allowed.
3. Reminders fire a configurable number of days before each order's target date, at the time you set in app Settings. Past-due orders will not generate new reminders.

## Can I use this with multiple bakers in the same business?

Not in this version. The app is single-user, single-device, with no account system or sync. CSV export and import is the only way to move data between devices.

## Is there cloud sync, iCloud sync, or backup?

Not in this version. iOS's automatic iCloud backup (Settings -> Apple ID -> iCloud -> iCloud Backup) will include the app's data as part of a full device backup, but that's it.

## How do I price a recipe?

1. Add your ingredients with their real purchase price and quantity.
2. Add packaging items (boxes, ribbons, bags, etc.) with price per package and units per package.
3. Create a product, set its sale price, and add the ingredients and packaging it uses.
4. The product detail page shows you the actual cost to make one piece, the profit per piece, and the profit margin.

## Contact

Email: **maxsoloshenko@gmail.com**

I read every email. Bug reports, feature requests, and feedback are all welcome.
