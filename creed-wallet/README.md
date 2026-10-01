# CREED Wallet

A classroom "crypto-style" wallet for CREED points that is safe for students of any age.
It is a single web page with no accounts, emails, sign-ups or real money, so no age requirement applies.

## How to use it

1. Open `index.html` in any browser (Chrome, Edge, Safari or Firefox). It works offline.
2. **Set up:** enter your class name and choose a teacher PIN.
3. **Students tab:** add each student with a first name or nickname and a PIN you give them. Each student gets a wallet address such as `CRD-7KQ2MX`.
4. **Award / Deduct:** pick one, several or all students, enter an amount and a reason.
5. **Class Store:** add rewards with a price and, if you want, a limited stock.
6. Students log in with their PIN to:
   - see their **balance** and full **transaction history**,
   - **buy** rewards from the class store,
   - set **savings goals** with progress bars,
   - stay within a **weekly spending limit** you set (budgeting),
   - **send** CREED to classmates (you can turn this off in Settings).

## The blockchain lesson built in

Every transaction stores a SHA-256 fingerprint of the transaction before it, which makes the ledger a hash chain like a blockchain.
On the **Ledger** tab, **Verify ledger** recalculates the chain. If anyone edits an old entry, it reports exactly which one was changed.

## Important limits

- **Data stays in one browser on one device.** This version works best on a single classroom computer or tablet that students take turns using. Use **Settings → Export backup** often. Clearing browser data erases the classroom unless you have a backup.
- PINs keep students out of each other's wallets, but this is classroom-level security, not bank-level. Use first names or nicknames only, and don't store sensitive information.
- To let each student use their own device, the next step would be a shared online database. That raises student-data privacy questions (FERPA/COPPA), so check your school's rules first.
