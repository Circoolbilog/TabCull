Temporary Readme!
#TabCull

TabCull is a Firefox extension designed to help you manage and declutter your browser by quickly closing or grouping all open tabs belonging to a specific domain. With a single click, you can easily close all tabs from any website, even if the URLs differ—making it a powerful tool for those who often end up with too many tabs open from the same site.
##Features

    Close All Tabs by Domain: Instantly close all tabs from a specified domain.
    Easy Access: Launch directly from the toolbar.
    Domain Prompt: Enter the domain name you want to close tabs for, giving you flexibility with each use.

##Installation

    Clone this repository to your local machine:

    git clone https://github.com/yourusername/TabCull.git

    Open Firefox and go to about:debugging.
    Select This Firefox in the sidebar.
    Click Load Temporary Add-on….
    Navigate to the TabCull directory, select the manifest.json file to load the extension temporarily for testing.

##Usage

    Click the TabCull icon in your Firefox toolbar.
    Enter the domain (e.g., example.com) for which you want to close all tabs.
    TabCull will close all tabs that belong to the specified domain, regardless of the URL path.

##Development
###File Structure

    manifest.json: Defines the extension's permissions and settings.
    background.js: Contains the core logic for querying and closing tabs by domain.

###Running Locally

To test changes, reload the extension in about:debugging after editing any files.
###Future Plans

    Add options for grouping tabs by domain.
    Implement a domain whitelist to preserve tabs from specific domains.
    Add a badge showing the number of tabs closed.

Contributing

Feel free to submit issues or feature requests. Contributions are welcome through pull requests.
License

This project is licensed under the MIT License. See the LICENSE file for details.
