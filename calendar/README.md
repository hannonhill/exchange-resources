# Calendar

Features include:

- [Themable](docs/theming.md) interactive calendar using the [Full Calendar jQuery plugin](http://arshaw.com/fullcalendar/).
- List view for events within selected category(ies).
- List view for events defined by terms.
- Folders for yearly and monthly organization of events.
- Landing Page for events within a given year or month.
- [Repeatable events](docs/repeat-options.md) using daily, weekly, monthly and yearly options.
- Multi-channel output for a variety of pages (XHTML, PDF, RSS, iCal, XML).
- Display events from [external resources](docs/external-sources.md) (Google Calendar Feed, XML, JSON, Cascade XML and Feed Blocks)

**Note:** This version makes use of the Velocity `#import` directive. For best results, import into an instance of Cascade running version 7.6 or greater; otherwise, the Formats being imported will need to be copied into the Format performing the import. Results may vary importing into 7.0.x, because of potential database structure changes and updates to how Dynamic Metadata are created/stored.

## Documentation

- [Repeating event options](docs/repeat-options.md)
- [Managing the Calendar](docs/managing-the-calendar.md)
- [Theming the Calendar](docs/theming.md)
- [Using external sources](docs/external-sources.md)


## Sample Cascade Server Exports
- #### Calendar-Examples.csse

  [Calendar-Examples.csse](Calendar-Examples.csse) has a few example single and recurring events, an external Google Calendar and sample customizations such as branding and social media icons.

  
- #### Calendar-Clean.csse

  [Calendar-Clean.csse](Calendar-Clean.csse) has no example events and is stripped of most customizations including headers, footers, and logos.

  
## Other Resources
- #### list-events.vm

  The [list-events Velocity Format](list-events.vm) will pull events (create a Content Type Index Block first) into another Site for showing upcoming events from the calendar. 

  **Note:** External sources are not applicable.

- #### sort-events.xml

  The [sort-events XSLT Format](sort-events.xml) is applied at either the Template or Configuration Set Level to sort those events being pulled into other Sites.

CSS:
- Updated fullcalendar.css and fullcalendar.print.css from v3.4.0 to v3.9.0.
- Removed bootstrap-responsive.css
- Modified calendar-extra.css and main.css to reflect changes in framework version & removed commented out styles.

JS:
- Modified jquery.hhcalendar.js to utilize the list view options for week and day calendars.
- Updated fullcalendar.min.js from v2.2.3 to v3.9.0.
- Updated gcal.js from v.2.2.3 to v3.9.0.
- Replaced jquery-ui-1.8.23.custom.min.js with jquery-ui.min.js (v1.12.1).
- Replaced jquery-1.8.1.min.js with jquery.min.js (v3.3.1).
- Updated moment.min.js from v2.8.4 to latest version.


Bug Fixes and Improvements:
- Full Calendar is now fully responsive.
- Modified several formats to reflect new framework CSS version.
- Fixed bug where single all-day events do not show up if there's an end date specified.
- Modified the display of timestamp for all day events.
- Fixed broken smart fields for event page's data definition.
- Fixed bug where dates were not showing in event popup.
- Added protect tags around document type for templates that may be affected by sorting XSLT format.
- Added list views for week and day view.





