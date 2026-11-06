# DeskMate away page

The away-from-home page for DeskMate OS. It holds no keys or settings: your DeskMate's
remote page (http://deskmate.local) shows a QR code with a link to this page. The link
carries DeskMate's relay channel and key after the `#`, which browsers never send to
the server hosting this page.

The page connects to the relay broker over secure WebSockets and encrypts every message
end to end with AES-256-GCM (WebCrypto), so neither this host nor the broker can read
or control your DeskMate.
