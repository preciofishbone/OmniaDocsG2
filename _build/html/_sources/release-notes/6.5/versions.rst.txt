6.5.5
========================================
(Omnia 6.5.4 / Workplace 6.5.4 / WCM 6.5.5 / MS 6.5.5)


- Fixed an issue that caused the wrong node to be selected in the new megamenu (#132987,#132730).
- Fixed an upgrade issue related to the footer (#133034).
- Fixed an issue related to route change when switching variations (#128842, #132943).
- Several stability improvements to Event Management (#133010).
- Fixed an issue that caused the User Profile Wizard to not open automatically when configured to do so (#132751).
- Updated language logic for Document Management Authoring Sites (#132626).


6.5.0
========================================
(Omnia 6.5.0 / Workplace 6.5.0 / WCM 6.5.0 / MS 6.5.0)


Major New Features 
**************************

(:doc:`More Details </release-notes/6.5/index>`)

- Workplace apps 
 - Dynamic Mega Menu (#115472, #125718, #114686).
 - Query by navigation path in page rollup.
 - Display logo for extra small screens (#126714).

- Enterprise glossary and the Taxonomy Navigation.
- New Provisioning Templates.
- Communities 2.0.
 - Its now possible to subscribe to Taxonomies.
 - Auto subscribe to newly created page. (#127971).
 - Permissions can now be setup so a page can only be edited by the Author.
 - New Comments and Activity Feed UI. (#115431, #120984)
 - Community Rollup.

- Section stepper.
- Governance dashboard including new metrics. 
- Graph client in Script/HTML.
- Search
 - Microsoft Search is now available as a search provider.
 - My Links can now be configured as a search category source (#130359).
 - The advanced search block can now be configured to use any search categories.
- Omnia Forms.
- Teams Channel block.
- People Card (Replaces opening and iframe to delve) (#125406, #126500, #129389)
- Yammer feed block.
- Teams Share Action on the Action button.
- Yammer Share Action on the Action button.
- Like Action for the Action button. (#)
- Automatic page translation, pages can now automatically create all variations without any editor intervention (#114074)
- Iframe block.
- Pages can now have documents stored as a property. 
- Its now possible to change the url of publishing apps after thier creation. 


Minor New Features
**************************
- Calendar rollup can now query data in a configurable timespan (#115468, #117523, #125845, #127240).
- Event management can now create event which includes a MS Teams meeting. A link to the meeting can be shown on the event.
- The filter state of a page rollup can now be stored as a query string.
- You can now show taxonomy properties on the page rollup card view.
- Show child nodes on cards in card view.
- New Scheduling workflow. A schedule rule can now be tied to any date enterprise property. (#116302).
- By using the new community’s layout feature, communities can now be provisioned in any language (#127432).
- The see more link of search can now be configured to show after each category (#121840).
- The profile image edit link for User Profile Completeness is now configurable. 
- The Action button now supports most of the actions in Omnia.
- Current publishing app is now a Query Scope on the Page Rollup.
- Sections now support many new modes. 
- Property replacement tokens are now available to create complex publishing app templates.
- Image sizes in the search results can move be set to a fixed size (#121952).
- Updated UX for the multilingual text input control.
- The scheduling flow has been updated to use a enterprise property instead of unique business rules.
- When archiving a page, you can now get a new draft from the old, published page.
- Newlines are now possible on shapes in OPM. (#120216, #120197)
- Description can now be shown in all rollups of App Instances.
- Updated UX for the people picker, the picker is always closed upon picking a value.
- 

Fixes
**************************
- Fixed an issue with clearing search refiner in Advanced search (#131147).
- Fixed an issue with the active tab color in OPM (#130939).
- Document picker sources now work as expected weather or not a document library has been configured on the publishing app (#119811).
- Animated GIFs can now be uploaded correctly (As long as they are not cropped or scaled) (#130619).
- Fixed an issue with the mail icon in the people rollup, it now works correctly in mobile (#130616).
- Several Document Management stability fixes and a move back to using CSOM APIs.
- Several Page Variation stability fixes.
- Updates to a theme mapping is now directly applied.
- Rendering terms in page properties now always renders new properties on a new row. (#129761).
- When sorting by likes, the most recent will show in top if several articles have the same number of likes (#121978).
- Fixed an issue with the Teamwork rollup that could occur when adding a new enterprise property (#130831).
- Several issue with saving images has been fixed (#126594).
- The add link action for the action button now correctly handles query strings (#128671)
- Fixes to preview issues (#132822, #132752, #131891, #132553, #131845, #132261, #131901, #128525)


For developers
************************
- All Vue chart types have been added.
