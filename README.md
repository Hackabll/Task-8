# Task-8
​Phase 1: Selection and Setup
​1. Choose a reputable free VPN and sign up
​Warning: Most "free" VPNs make money by selling your data. For this exercise, use a "Freemium" service (a reputable paid company that offers a limited free tier).
​Recommendation: Proton VPN is widely considered the safest free option because it has no data limits and a strict no-logs policy.
​Alternative: Windscribe (10GB/month limit) or TunnelBear (500MB limit).
​Action: Go to the official website (e.g., protonvpn.com) and sign up for the free plan.
​2. Download and install the VPN client
​Download the app for your specific device (Windows, macOS, or Mobile).
​Run the installer and follow the on-screen prompts.
​Note: You may need to grant the app permission to add "VPN Configurations" to your device's network settings. This is normal.
​3. Connect to a VPN server
​Open the application and log in.
​Find the "Quick Connect" button or select a specific country from the list (e.g., USA, Netherlands, or Japan).
​Wait for the status to change to Connected (usually turns green).
​Phase 2: Verification
​4. Verify your IP address has changed
​Before connecting (if you haven't already), go to whatismyipaddress.com and write down your "ISP" (Internet Service Provider) and "City".
​After connecting, refresh the page.
​Result: You should now see a completely different IPv4 address, and the "ISP" should list the VPN company (e.g., "Proton AG") instead of your actual internet provider (e.g., Verizon, Comcast, Jio).
​5. Browse a website to confirm traffic is encrypted
​Clarification: You cannot "see" the encryption just by looking at a website; the VPN works in the background like a secure tunnel. If the website loads, the tunnel is working.
​Better Test: Go to dnsleaktest.com.
​Click Standard Test.
​Result: If the results show servers owned by your VPN provider (and not your actual ISP), your traffic is successfully encrypted and routed through the secure tunnel.
​6. Disconnect VPN and compare
​Speed Test: While connected, run a test at speedtest.net. Note the Download/Upload speeds and Ping (Latency).
​Disconnect: Turn off the VPN in the app.
​Retest: Run the speed test again.
​Comparison: You will likely notice that your internet is faster and "snappier" (lower ping) without the VPN. This is the trade-off for encryption.
​Phase 3: Research and Summary
​7. Research VPN encryption and privacy features
​Encryption Standard: Look for AES-256, often called "military-grade encryption." It would take a supercomputer millions of years to crack it.
​Protocols: These are the instructions the VPN uses to create the tunnel. Common ones are OpenVPN (reliable, standard) and WireGuard (newer, faster, lighter).
​Kill Switch: A critical feature that cuts your internet connection instantly if the VPN drops, preventing your real IP from leaking for even a second.
​No-Logs Policy: A promise that the VPN provider does not keep records of what websites you visit.
