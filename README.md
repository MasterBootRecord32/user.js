# Presentation
My Firefox configuration that allies privacy to practicality and simplicity. This user.js file is based on the work of <a href="https://github.com/yokoffing"> Yokoffing </a> on <a href="https://github.com/yokoffing/Betterfox"> Betterfox </a>, to which I've applied a series of tested modifications. 

# Features
- Increased speed for modern browsing experience, even on bloated sites;
- Better privacy than with default config: language spoofing, timezone spoofing in pb mode, stricter custom tracking protection, Mullvad DoH, disabled Google's Safe Browsing, Location services set to a more private alternative, HTTPS only, clear data on shutdown, no DRM, etc);
- Disable useless features for a distraction-free browsing experience (pocket, ai features, sponsored sites);
- Enhanced smooth scrolling (kinetic scrolling, adjusted sensitivity and speed).

**WARNING: some parameters I have applied in this compilation breaks certain websites (mainly video communication and social media platforms), mainly because of network.http.referer.XOriginTrimmingPolicy, media.navigator.enabled and browser.contentblocking.category having really strict values.**

# Installation
1. Backup your profile :
  - Open Firefox and go to `about:profiles` ;
  - Check for your actual active profile ("Default Profile" should be "yes") ;
  - On the line displaying "Root Directory", click "Open Directory" ;
  - Close Firefox and copy all the directory's content ;
  - Go to this profile's parent directory in your file manager and create a new folder ;
  - Paste the contents into it ;
  - Rename the folder after the name of your profile (for a profile called `kshj81bf.default`, the backup copy might be called `kshj81bf.default.bak`).
2. Clone this repository in your home directory ;
3. Review the file's content and make changes if needed ;
4. Move `user.js` to your user's firefox profile directory :
  - Open back Firefox and go to `about:profiles` ;
  - For the profile you want to use, on the line displaying "Root Directory", click "Open Directory" ;
  - Paste the user.js file in the directory ;
5. Restart Firefox.

# Test the configuration
You can test your Firefox configuration from a privacy standpoint using the Electronic Frontier Foundation's <a href="https://coveryourtracks.eff.org/"> tracker and fingerprinting test </a>.

# Credits
- <a href="https://github.com/yokoffing"> Yokoffing </a> for their work on <a href="https://github.com/yokoffing/Betterfox"> Betterfox </a>;
- <a href="https://github.com/arkenfox"> Arkenfox </a> for their work on <a href="https://github.com/arkenfox/user.js/"> Arkenfox User.js </a>;
- <a href="https://www.mozilla.org/en-US/firefox/new/"> The Firefox Team </a> for their amazing work on this browser ;
- <a href="https://eff.org/"> The Electronic Frontier Foundation </a> for their comprehensive <a href="https://coveryourtracks.eff.org/"> tracker and fingerprinting test </a>;

# WARNING !
THIS CODE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE CODE BE LIABLE FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE CODE OR THE USE OR OTHER DEALINGS IN THE CODE.
