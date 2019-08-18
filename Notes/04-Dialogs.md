# I, Chatbot

Table of Contents

* [Part 1 - First Bot](01-FirstBot.md)
* [Part 2 - QnA Maker](02-QnAMaker.md)
* [Part 3 - Bot State](03-State.md)
* [Part 4 - Dialogs](04-Dialogs.md) <-- this section
* [Part 5 - LUIS](05-LUIS.md)
* [Part 6 - Adaptive Cards](06-AdaptiveCards.md)
* [Part 7 - Calling back-end services](07-CallingServices.md)

## Dialogs

![Slide](./Slides/Slide30.PNG)

See [Design and control conversation flow](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-design-conversation-flow?view=azure-bot-service-4.0) for more details.

![Slide](./Slides/Slide31.PNG)

![Slide](./Slides/Slide32.PNG)

Here's [an overview](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-dialog?view=azure-bot-service-4.0) of dialogs in Bot Framework v4. I found [this, more succinct article](https://www.brightdevelopers.com/overview-of-dialogs-for-bot-framework-v4/) helpful as well.

If you want to add branching and looping to your dialogs, check out [Create advanced conversation flow using branches and loops](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-complex-conversation-flow).

![Slide](./Slides/Slide33.PNG)

![Slide](./Slides/Slide34.PNG)

Prompt options are detailed here ([.NET](https://docs.microsoft.com/en-us/dotnet/api/microsoft.bot.builder.dialogs.promptoptions), [Node](https://docs.microsoft.com/en-us/javascript/api/botbuilder-dialogs/promptoptions)).

![Slide](./Slides/Slide35.PNG)

The [Multi-turn prompt sample](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-conversation-flow) shows a sequence of several prompt dialogs called by a waterfall dialog.

![Slide](./Slides/Slide36.PNG)

Notice that the bot saves state at the end of each turn.

![Slide](./Slides/Slide37.PNG)

Walk through the [Consuling Bot dialogs](../ConsultingBot/ConsultingBot/Dialogs/).

### [The next section is here](05-LUIS.md)

## Repos used in this workshop:

1. [https://github.com/BobGerman/Bots](https://github.com/BobGerman/Bots): Bob's repo, containing samples specific to this workshop, and these notes

1. [https://github.com/microsoft/BotBuilder-Samples](https://github.com/microsoft/BotBuilder-Samples): Great samples for Bot Framework v4

1. [https://github.com/OfficeDev/msteams-samples-outgoing-webhook-nodejs](https://github.com/OfficeDev/msteams-samples-outgoing-webhook-nodejs): Outgoing webhook - the simplest bot for Teams

1. [https://github.com/OfficeDev/BotBuilder-MicrosoftTeams-dotnet](https://github.com/OfficeDev/BotBuilder-MicrosoftTeams-dotnet): Beta of Teams .NET SDK for Bot Framework v4; samples are included

1. [https://github.com/OfficeDev/BotBuilder-MicrosoftTeams-node](https://github.com/OfficeDev/BotBuilder-MicrosoftTeams-node): Beta of Teams Node SDK for Bot Framework v4; samples are included

1. [https://github.com/coolc0ders/Real-Proactive-Message-Bot:](https://github.com/coolc0ders/Real-Proactive-Message-Bot): Shows how to build a "proactive" bot for Teams - i.e. the Bot initiates conversation

1. [https://github.com/OfficeDev/msteams-sample-contoso-hr-talent-app.git](https://github.com/OfficeDev/msteams-sample-contoso-hr-talent-app.git): Great Teams bot/app sample but it's v3
