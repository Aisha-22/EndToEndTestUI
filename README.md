EndToEndTestUI
About the project:
*End to End Automation using all UI Elements with selenium
https://www.spicejet.com/

**Challenges
The challenge experienced was 'ParentChild Relationship' the code structure on the website changed from an <a/> tagName to 'Option' list.
To select from a list using ParentChild xpath after the space you need to use a single slash '/' and not a double slash '//'
ParentChild Syntax: 
//tagName[@attribute='vale'] /tagName[@attribute='value']
//*[@id='ctl00_mainContent_ddl_destinationStation1'] /option[@value='KQH']

The other challenge faced was the Validating if UI Elements are disabled or enabled with Attributes