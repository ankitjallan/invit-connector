# InvIT Connector

The Windows installer that links a TallyPrime computer to [InvIT](https://invit.fly.dev), the inventory and billing service from Authentic Technologies.

**Download:** [InvIT-Connector-Setup.exe](https://github.com/ankitjallan/invit-connector/releases/latest/download/InvIT-Connector-Setup.exe). Each release lists the file's SHA-256 so you can check what you downloaded.

## Installing

1. In InvIT, open **Tally sync → Connect a Tally computer** and copy the pairing code. It works once, for 24 hours.
2. On the computer that runs TallyPrime, right-click the installer → **Run as administrator**, and enter the code when it asks. Windows may say it "protected your PC" because the installer is not code-signed yet. Click **More info → Run anyway**.
3. Keep TallyPrime open with your company loaded and its XML server on (F1 → Settings → Connectivity, port 9000).

The installer is useless without a pairing code from an InvIT administrator. For help, contact Authentic Technologies.

This repository only hosts the installer. The source code is private.
