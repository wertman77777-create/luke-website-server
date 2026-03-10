# Setup Guide

Follow these steps to connect to the media server.

## Step 1: Install Tailscale

The server is hosted on a private network for security. To access it, you need to be on the **Tailscale** network.

1.  **Download Tailscale:** Go to [tailscale.com/download](https://tailscale.com/download) and install it on your device (Phone, PC, or Tablet).
2.  **Sign In:** Open the app and sign in using the email address I provided to you.
3.  **Verify Connection:** Once signed in, you should see the server (it might be named `luke-server` or similar) in your list of devices.

---

## Step 2: Access Jellyfin

Once Tailscale is connected, you can access the media library.

### Option A: Web Browser
Simply click the link below or type it into your browser:
[http://100.77.87.28:8097](http://100.77.87.28:8097)

### Option B: Mobile App (Recommended)
1.  Download the **Jellyfin** app from your app store.
2.  Open the app and click **"Add Server"**.
3.  Enter the server address: `http://100.77.87.28:8097`
4.  Log in with your username and password.

---

## Troubleshooting

- **Can't connect?** Make sure Tailscale is turned "On" (it should show a VPN icon on mobile).
- **Video buffering?** Check your internet connection. The server handles most of the work, but a stable connection helps!
- **Need a login?** Contact me to get your account details.
