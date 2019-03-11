# Calendar
Features include:

- Themable interactive calendar using the [Full Calendar jQuery plugin](https://fullcalendar.io/).
- Calendar Grid for month view, list view for week and day view. Filterable by category(ies).
- List view for events within selected category(ies).
- Folders for yearly and monthly organization of events.
- Landing Page for events within a given year or month.
- Repeatable events using daily, weekly, monthly and yearly options.
- Multi-channel output for a variety of pages (XHTML, RSS, iCal, XML).
- Display events from external resources (Google Calendar Feed, XML, JSON, Cascade XML and Feed Blocks)

# v0.8.x
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

Current Site was exported using Cascade CMS 8.11.1
