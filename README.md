Lab: Basic Network Traffic Analysis
What I did:
I used Wireshark to capture and analyze my own Wi-Fi traffic.
What I found:
 After filtering by ⁠dns⁠, I saw my device connecting in the background to services like Adobe, 360 Total Security, and Microsoft.
 I could see my local IP in the Source column and where each service was heading.
 I also noticed some "Malformed Packet" DNS entries, which I want to look into later to see why they’re happening.
 I saw TLS encrypted packets. I learned that TLS encrypts the actual data, but the IP addresses stay visible so the connection can work.
My takeaway:
This was a cool way to see what my computer is actually doing behind the scenes. Even when I’m not doing anything, there is constant traffic happening on my network
