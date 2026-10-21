MAN CHAIN — COMPLETE WEBSITE SOURCE

Included files
- index.html: MAN Chain landing page, based on the supplied screenshot; the roadmap timeline section is removed.
- styles.css: landing page styling and responsive layouts.
- script.js: mobile navigation menu.
- account.html: separate bilingual Vietnamese/English account and wallet page with login/register forms and MetaMask/Keplr connection buttons.

How to use with GitHub Pages
1. Extract this ZIP.
2. Upload all files into the ROOT of your existing MAN-Chain repository, next to one another.
3. Keep the filenames exactly as they are.
4. Do not delete index.html; it remains the homepage.
5. After GitHub Pages updates, the home page is the repository Pages URL, and the account page is at the same URL followed by /account.html.

Important limitations
- This is a frontend starter, not a production-ready wallet or account service.
- Registration/login forms are demo-only and do not create real accounts or authenticate users. Connect a secure backend/auth provider before collecting real credentials.
- MetaMask works only where its provider is available. For dependable iOS/Android wallet support, integrate and test WalletConnect or official wallet deep links.
- Keplr code currently uses Cosmos Hub (cosmoshub-4) as a demo chain. Replace it with MAN Chain's real chain ID/RPC/network configuration when available.
- The account page displays a sample 0.00 MAN balance; it does not read a real balance.
- Never ask users to enter a seed phrase or private key on your website.
- The landing page is a visual recreation of the reference screenshot, not a pixel-perfect copy of original artwork.
