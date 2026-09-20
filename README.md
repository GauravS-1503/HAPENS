# HAPENS Prototype

HAPENS is a mobile-first patient dashboard prototype for cancer hospital enrolment, appointments, sample report tracking, payments, and in-hospital navigation.

## GitHub Pages

GitHub Pages serves the prototype from the repository root through `index.html`.

After pushing changes, open:

```text
https://gauravs-1503.github.io/HAPENS/
```

## Run locally

```powershell
node scripts/serve-local.mjs
```

Open the app on this PC at:

```text
http://localhost:5173
```

To preview on a phone, connect the phone and PC to the same Wi-Fi and open:

```text
http://192.168.1.4:5173
```

If the phone cannot connect, allow Node.js through Windows Firewall for private networks.

## USB preview option

For Android USB preview with platform tools installed:

```powershell
adb reverse tcp:5173 tcp:5173
```

Then open this on the phone:

```text
http://localhost:5173
```

## Git upload

The project has been initialized for Git. To upload it to GitHub or another Git host:

```powershell
git add .
git commit -m "Create HAPENS patient dashboard prototype"
git branch -M main
git remote add origin <your-repository-url>
git push -u origin main
```
