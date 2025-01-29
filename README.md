# Adobe DNS Filter

This simple script allows you to filter Adobe-related domains and IPs.

### Known side effects

This might lead to some Adobe-related sites (like Adobe Login and Adobe Stock) to not load. If this happens, remove the script temporarily using the `--remove` argument, then reapply when you want to use Adobe Software again.

## How to use

1. Download the script from the [releases page](https://github.com/YarosMallorca/adobe_dns_filter/releases/latest)

2. Run the script:

   On Windows:

   - Open Terminal as Administrator
   - cd to the directory with the script exe file
   - Run the script with the `--apply` argument

   On macOS:

   - Open Terminal
   - cd to the directory where the script is located (usually it is your Downloads folder (```cd ~/Downloads```))
   - Make the script executable with `chmod +x adobe_deactivation_bypass_mac`
   - Run the script as root with the `--apply` argument

3. Done!

To remove it, simply re-run it with the `--remove` argument.
