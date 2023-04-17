## General Testing Strategy

For our project, we are employing CI/CD with Github for basic testing for issues preventing our app from building. This is ultimately to keep us from merging in bad code since Netlify will build and publish our branch main to production. Outside of CI/CD, we'll implement snapshot tests to ensure the visuals we're getting back are loading appropriately and unit tests to see if functions are returning appropriate values.

1.  InitiativeCardStandardSnapshot

    1.  See if standard initiative card is loading full data correctly

    2.  Standard initiative card is loading full data properly

    3.  Input: dummy data for initiative card standard

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

2.  InitiativeCardPartialDataSnapshot

    1.  See if standard initiative card is loading partial data correctly

    2.  Standard initiative card is loading partial data properly - default states load

    3.  Input: partial dummy data for initiative card standard

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

3.  InitiativeCardAccountSnapshot

    1.  See if account style initiative card is loading full data correctly

    2.  Account style initiative card is loading full data properly

    3.  Input: dummy data for initiative card account

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

4.  NewsCardStandardSnapshot

    1.  See if standard news card is loading full data correctly

    2.  Standard new card is loading full data properly

    3.  Input: dummy data for news card 

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

5.  NewsCardCarouselSnapshot

    1.  See if news card carousel style is loading full data correctly

    2.  News card carousel style is loading full data properly

    3.  Input: dummy data for news card 

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

6.  NewsCardCarouselFeatureSnapshot

    1.  See if news card feature style is loading full data correctly

    2.  News card feature style is loading full data properly

    3.  Input: dummy data for news card 

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

7.  AddTagSnapshot

    1.  See if tags component is adding tag as expected

    2.  Tags component adds tag pill underneath and clears input once user clicks add button

    3.  Input: tag value

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match 

8.  DeleteTagSnapshot

    1.  See if tags component removes pill when pill's delete button is clicked

    2.  Tags component delete tag pill underneath once delete button is clicked

    3.  Input: none

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match

9.  UserAdminFunctionsInitiativeSnapshot

    1.  Verify user can view admin function on an initiative if that user is an admin/creator of initiative

    2.  Admin features are visible when user clicks into initiative they've made/are admin of

    3.  Input: none

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match

10. CreateNewEventSnapshot

    1.  Verify new event is created for an initiative 

    2.  Creating an event adds initiative event card to event list

    3.  Input: event data

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match

11. CreateNewAnnouncementSnapshot

    1.  Verify new announcement is created for an initiative 

    2.  Creating an announcement adds announcement card to announcement list

    3.  Input: announcement data

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match

12. OpenEventModalSnapshot

    1.  Verify event modal renders on click 

    2.  Event modal opens when trigger is clicked

    3.  Input: event data

    4.  Return passed with message if snapshots match

    5.  Return failure with message if snapshots do not match