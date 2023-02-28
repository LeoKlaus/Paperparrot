# Paperparrot

Paperparrot is and will be available for Apple Devices (iPhone, iPad and Mac) only.<br/>
<a target="_blank" href='https://apps.apple.com/us/app/paperparrot/id1663665267'>
    <img alt='Get Paperparrot on the App Store' src='images/AppStoreBadge.svg' height="60" />
</a>
There is also a Discord now to discuss the app: [Join here](https://discord.gg/xa6hTS3GU8)

## What is this app?
Paperparrot originated as a client for the awesome Paperless-ng(x), a document management system that you can host on your own infrastructure like a NAS, homeserver or a server you rent in the cloud.
During early development, I have realized that setting up and maintaining a server is prohibitively complicated and requires quite a big time investment. Thus, I have put more and more time and effort into making the app work offline, completely without a server.

At this point, almost the full functionality of Paperless-ng(x) is available locally, without the need for a server. Setup is as simple as downloading the app and adding documents.
Still, all documents and custom attributes are available on all of your devices via iCloud.

Of course, the integration with a Paperless-ng(x) server is still a major part of the app. Users can simply enter the credentials to their servers and be ready to go, it even offers functionality some of the other client apps don't have, like spotlight integration, keeping documents available offline or support for saved views.
For a deeper dive into available features, read #Features below.


## Why the name?
Even though I do plan on making the source code publicly available at a later point, [Paperparrot is not and will never be free software or open source](https://en.wikipedia.org/wiki/Source-available_software#Distinction_from_free_and_open-source_software). 
Despite being fully compatible to Paperless-ng(x), I want to clearly separate Paperparrot from Paperless in both name and branding as both provide similar but distinct features, in parts target a different audience and follow different development philosophies.


## What does it do?
Let me start off by telling you what it **doesn't** do:<br/>
**Paperparrot is not a backup solution.** While I put great care into keeping Paperparrot reliable and safe, it does not replace keeping a separate backup of your important files.


#### Now that we got that out of the way, what **does** Paperparrot do?
Paperparrot makes the handling and organization of both physical (paper) and digital documents easier. It does this by offering a selection of custom attributes, like tags, document types or correspondents, you can apply to your documents. Documents can be searched and sorted by any of these attributes. When adding a document to Paperparrot, it's content is scanned and analyzed (locally, on your device) and attributes are assigned automatically based on your preferences. Once you have everything set up, the workflow for adding a document can be as simple as pressing the button and scanning the document. There's an [example in the wiki](https://github.com/LeoKlaus/Paperparrot/wiki/Usage-Example) if you would like one.

## What if I have an issue with Paperparrot?
Please create a bug report at [issues](https://github.com/LeoKlaus/Paperparrot/issues/new/choose). Follow the guidelines for creating an issue and provide as much information as possible without revealing any personal data. Please check if a bug has already been reported before creating a new issue.


## It would be nice if Paperparrot could...
I collect feature requests and ideas for improvement in [the discussion section of the repository](https://github.com/LeoKlaus/Paperparrot/discussions). You can create feature requests and vote on other ideas [here](https://github.com/LeoKlaus/Paperparrot/discussions/new/choose). Please check if a similar feature has been requested before and vote on that instead of creating a duplicate.


## What exactly is a...
Generally, there are no rules for what attributes to apply how. If you need some inspiration, this is how the attributes where designed to be used:
- Correspondent: The person or institution that is either recipient or issuer of a document. 
- Document Type: The document type describes what kind of document it's applied to. This could be something like "Paycheck", "Certificate"... 
- Tag: A tag can contain all kinds of information, a single tag can be assigned to many documents and a single document can have many tags. You can use tags to store all the important information that doesn't fit the correspondent or document type attributes. 
- Created At: The date a document was originally issued at. 
- ASN: The archive serial number (short: ASN) is a unique identifier for the document. This can help you to make sorting and archival of physical documents easier.
