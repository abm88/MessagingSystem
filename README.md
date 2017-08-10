# MessagingSystem
Challenge Project
Business Portfolio Case
XYZ insurance company, an insurance company that has 2 million customers Nationwide; As an insurance company they are required to communicate constantly with their customers to keep them informed about their products, inform them of the status of their policies and engage them about changes.
To enable XYZ communicate to their numerous customers, they have acquired a messaging service which sends out messages across different channels (email, sms and print) to their policy holders. On a daily bases they send about 20 thousand policy driven messages. This is achieved by sending a batch of policy data from their policies holding system to the messaging service which will validate and process the data.






Problem description
As part of the validation process, the XYZ’s Data team would like to be extracted any policy document that does not meet the channel requirement. That is where key fields are missing from the data, for example SMS channel requires a mobile phone number, e-Mail requires an email address and Print requires a postcode to be present. They will also like a report showing which records have been extracted to allow for them to be actioned.

A policies data file has been provided below; this contains the data feed as provided by XYZ. You are required to write an application that will validate this data file based on the above problem description.
 
Policy Data Structure description
header-PolicyDocumentation-XXXXXXXXXXX   ------ marks the start of a policy
end-PolicyDocumentation-XXXXXXXXXXX      ------ marks the end of a policy, 
Where XXXXXXXXXXX is the policy number
Within a policy there are entries that are defined by Key Value pairs delimited by linefeed. The key value pair is delimited by the '=' character.
