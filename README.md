otrs2mbox
=======

Download otrs ticket to mbox

CONFIG
------------

By default getotrs attempts to load `~/.getotrs` as config file, which can be
used to configure username/url/password. See example file.

OTRS WebService
------------

otrs2mbox.yml includes an service description, in otrs 4.0.1 it is possible to import this service description
with the GenericInterface Webservices administration tool. The URL for this WebService is:

 https://otrs.url.de/otrs/nph-genericinterface.pl/Webservice/getotrs/TicketGet/

TRIVIA
------------

Only mail text is fetched, no attachments.
