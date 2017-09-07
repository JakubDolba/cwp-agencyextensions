# Changelog

## 1.1.0 (2017-09-08)

* NEW Add config static to prevent editor.css from being used by user code (Robbie Averill) - e22ed4f
* Update branch alias for 1.1.x-dev (Robbie Averill) - c146476
* Remove obsolete branch alias (Robbie Averill) - b96fb1b

## 1.0.1 (2017-07-04)

* FIX Add configuration option to disable default theme assets (Robbie Averill) - e113f96
* FIX Ensure users can add custom styles and scripts with extensions and works in Security (Robbie Averill) - 76ddd70

## 1.0.0 (2017-06-02)
## 1.0.0-rc1 (2017-05-15)

* API Allow "default" theme installations that are renamed to use default theme styles and scripts (Robbie Averill)

## 1.0.0-beta1 (2017-03-20)
## 0.4.0 (2017-03-16)

* Change CwpThemeHelper to singleton and deprecate in 2.0 (Damian Mooyman)
* API Add CwpThemeHelper to provide functionality for using/checking against CWP themes (Robbie Averill)
* CWPT-417: Add extension to remove icons in home page for non-default theme (Robbie Averill)
* FIX Remove theme condition for including FA plugin, enabled by default. Update docs to reference. (Robbie Averill)
* DOCS Remove section from FontAwesome plugin docs regarding requiring "starter" theme, add note for frontend stylesheet. (Robbie Averill)
* Add BSD-3 clause license (Robbie Averill)
* Add gitattributes with export-ignore for "docs" folder (Robbie Averill)
* CWPT-385: Simplify documentation, moved to "cwp" module. Add some flexibility around FontAwesome plugin config. (Robbie Averill)
* FIX replaced tinyMce function for adding buttons from insertButtonAfter to addButtonsToLine - FontAwesome feature now displays in CMS (Paul Jayme)

## 0.3.0 (2017-03-09)

* CWPT-439: Add hero to Carousel headings in CMS and add help tips to explain the difference between them, and recommendations for content (newleeland)
* CWPT-313: Add tagline back in for starter/watea themes (Robbie Averill)
* Move translations for custom CWP siteconfig from "cwp" to agency-extensions (Robbie Averill)
* API Move CustomSiteConfig settings from cwp/cwp to agency-extensions, tidy up config (Robbie Averill)
* API Remove getSelectedLanguage from SiteTree extension, moved to "cwp" module (Robbie Averill)
* Remove custom search behaviour and rely on base page search Modify dependencies to cwp/cwp 1.6 (Damian Mooyman)
* Remove tests (Damian Mooyman)
* Remove form extensions (Damian Mooyman)
* API Remove CarouselItemExtension and merge behaviour into CarouselItem (Robbie Averill)
* Add translations for carousel items (Robbie Averill)
* API Move carousel from "cwp" to "agency-extensions". Add "default" theme functionality. (Robbie Averill)
* Remove FormFieldsPage (moved to demo site) (Damian Mooyman)
* CWPT-374: Remove DatedUpdateHolderExtension - moved to "cwp" module (Robbie Averill)
* CWPT-375: Remove CWPBasePageExtension - locale addition has been moved to "cwp" module (Robbie Averill)
* FIX Rename module paths from cwp-theme-module to agency-extensions (Robbie Averill)
* CWPT-387: Remove contact-us user form population, it has been moved to "cwp" (Robbie Averill)
* Update theme names from new-theme to starter, remove unneeded VCS repository (Robbie Averill)
* Rename module Remove nested repository (Damian Mooyman)
* CWPT-361: Remove linting git hook and reference from documentation (Robbie Averill)
* Adding a new icon set as a new button in the CMS which allows user to apply icons on both the front-end and back-end (Paul Jayme)

## 0.2.0 (2017-03-02)

* CWPT-342: Add placeholder and description to some contact user form example fields (Robbie Averill)
* CWPT-341: Add extension to create "contact us" user defined form (Robbie Averill)
* FIX Rename CWPCleanupSiteConfigExtensionTest to CWPSiteConfigExtensionTest (Robbie Averill)
* CWPT-339 Add Upload secundary footer logo in the CMS (Matias)
* CWPT-306: Add support for user forms templates and configuration (Robbie Averill)
* Adding new extension to show a results string based on the filters of news and events pages (Paul Jayme)
* API Add extension to provide locale code with available translations (Robbie Averill)
* CWPT-320: Implement a carousel in a jumbotron style (Robbie Averill)
* CWPT-320: Add Jumbotron HTML editor to its own tab in the CMS for HomePages (Robbie Averill)
* CWPT-303: Update documentation to include installation, requirements and some extra notes about purpose (Robbie Averill)
* CWPT-284: Add centralised logic for ID retrieval, aria-describedby attribute and allow periods in currency fields (Robbie Averill)

## 0.1.0 (2017-02-16)

* CWPT-271: Add translatable defaults for the empty and no search result phrases. Add tests. (Robbie Averill)
* Set a session-message if any error has been detected. Message is translatable/updatable. (Simon Erkelens)
* Remove form control class (Mikaela Young)
* Remove onneeded fields. Add descriptions demo. (Simon Erkelens)
* FieldTypes set correctly. (Simon Erkelens)
* CWPT-84 search fields in siteconfig. (Simon Erkelens)
* CWPT-194_optionset_checkboxset_classes (Mikaela Young)
* Remove aria-required from fields that don't support it. (Simon Erkelens)
* Added a few more required fields (Christopher Pitt)
* Search title (Simon Erkelens)
* Modified HTMLEditor to add custom bootstrap style for blockquotes (Paul Jayme)
* CWPT-40 Search (Simon Erkelens)
* CWPT-37-redo-forms (Christopher Pitt)
* CWPT-83 demo form (Christopher Pitt)
* Added getter for local name (Christopher Pitt)
* Initial form and added classes in the extension. (Simon Erkelens)
* Initial form (Simon Erkelens)
* CWPT-71 clean up SiteConfig (Christopher Pitt)
* Module should not require theme (Simon Erkelens)
* Documentation for the githook (Simon Erkelens)
* Make composer have some logic. Pre commit and composer update (Simon Erkelens)
* Initial commit (Simon Erkelens)