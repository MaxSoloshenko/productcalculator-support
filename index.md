# ProductCalculator Support

ProductCalculator is a bookkeeping app for home bakers and small bakery owners. This page covers the most common questions.

## Where is my data stored?

Everything you enter is stored locally on your iPhone or iPad using Apple's SwiftData framework. Nothing is uploaded to any server. The app does not connect to the internet.

## How do I back up my data?

Open the app, scroll to the **Manage** section at the bottom of the dashboard, and tap the **Settings** row (gear icon). Scroll to the **Data Tools** card and tap **Export CSV**.

The app writes 10 CSV files into a folder called `BakeryCSVExport` and immediately opens a share sheet with a single `BakeryCSVExport.zip` containing all 10 files. From there you can:

- **AirDrop** the zip to your Mac.
- **Save to Files** -> iCloud Drive (or anywhere else) for a cloud backup.
- **Mail** the zip to yourself.
- Pick any other destination iOS offers (Messages, Notes, third-party apps).

If you'd rather browse the raw CSV folder directly, open the iOS **Files** app -> **Browse** -> **On My iPhone** -> **ProductCalculator** -> **BakeryCSVExport**. The 10 individual CSV files live there and update on each export.

## How do I move my data to a new device?

1. On the old device, tap **Export CSV** and AirDrop (or otherwise transfer) `BakeryCSVExport.zip` to the new device.
2. Unzip on the new device (long-press the zip in Files -> Uncompress).
3. Install ProductCalculator, open **Settings -> Data Tools**, and tap **Import CSV**. Select all 10 CSV files at once from the unzipped folder.

## What does "Clear All Data" do?

It permanently deletes every ingredient, packaging item, product, recipe, sale, order, expense, and price history record stored on your device. It also cancels any pending order reminders. Your business profile (name, currency, initials) is not affected. This action cannot be undone, so export a CSV backup first if you want to keep your data.

## Notifications are not arriving

1. In the app, scroll to **Manage -> Settings** on the dashboard. In the **Notifications** card, confirm **Schedule reminders** is on.
2. Open the iOS **Settings** app -> **Notifications** -> **ProductCalculator** and confirm notifications are allowed.
3. Reminders fire a configurable number of days before each order's target date, at the time you set in app Settings. Orders whose target date is already in the past will not generate new reminders.

## Can I use this with multiple bakers in the same business?

Not in this version. The app is single-user, single-device, with no account system or sync. CSV export and import is the only way to move data between devices.

## Is there cloud sync, iCloud sync, or backup?

Not in this version. iOS's automatic iCloud backup (Settings -> Apple ID -> iCloud -> iCloud Backup) will include the app's data as part of a full device backup, but that's it.

## How do I price a recipe?

1. Add your ingredients with their **purchase price** and **purchase quantity** (e.g. one 25-lb bag of flour for $18 -> price 18, quantity 25, unit lb).
2. Add packaging items (boxes, ribbons, bags, etc.) with their **purchase price** and **purchase quantity** (e.g. a 50-pack of cake boxes for $30 -> price 30, quantity 50, unit pieces). The app calculates cost per piece for you.
3. Create a product, set its **sale price**, and add the ingredients and packaging it uses.
4. The product detail page shows you the cost per piece, profit per piece, and profit margin.

## Contact

Email: **maxsoloshenko@gmail.com**

I read every email. Bug reports, feature requests, and feedback are all welcome.
