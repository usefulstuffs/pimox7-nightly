# Starting a CT
Video showing CT and VM configuration: [PiMox7 - RPi4 - arm64 CT & VM Basic Configuration](https://youtu.be/LGb7fB1wK4Q).

### Download CT Image
1. Follow the link below to download the CT image
   1. Access the following link in your browser.
   - http://vichingo455.ddns.net/pimox/pimox7/ct-lxc-templates/
   2. Dig deeper into the links, focusing on OS distributions and versions, and CPU architectures. And Select arm64 as the architecture.
   3. Rename and store the downloaded files in the LXC folder.

### Make CT using Web-UI:
2. Click 'Create CT' in upper right
#### Under 'General'
   - Set 'Hostname'
   - Set 'Password'
   - Set 'Confirm password'
#### Under 'Template'
   - Set 'Template' to the file name from the previous step
#### Under 'Network' 
   - Set 'IPv4' to Select Static or DHCP
   - If you select Static, Set 'IPv4/CIDR' and Gateway
   - Set 'IPv6' to Select Static or DHCP or SLAAC
   - If you select Static, Set 'IPv6/CIDR' and Gateway
