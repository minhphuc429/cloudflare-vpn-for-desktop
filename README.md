# Cloudflare VPN WARP+ 1.1.1.1 for your Desktop (Windows, MacOSX, Ubuntu...)
This repository is to help you with installing CloudFlare VPN (1.1.1.1) on your Desktop(Windows, MacOSX, Ubuntu...)
### Please follow steps below to get stuffs done

1. Install Wireguard on your OS. You can easily get it from here https://www.wireguard.com/install/
2. Go to https://labs.play-with-docker.com/ and login to the page (If you haven't got an account there, sign up a new one, it might take some minutes to complete)
3. Once you are in the session, add a new instance and execute the following command (you can copy and paste to command line)

`git clone https://github.com/cyberman219/cloudflare-vpn-for-desktop/; cd cloudflare-vpn-for-desktop; ./generator.sh`

4. Once the script finished generating the config files, access the link via port 80 *highlighted once finished* and download 2 files *wgcf-identity.json* and *wgcf-profile.conf* to your PC. 
5. Last step, import the *wgcf-profile.conf* config file to Wireguard and enjoy your VPN
