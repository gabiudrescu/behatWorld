Behat World
===========

This started as an idea of grouping on one page all tools and extensions available for [Behat](http://behat.org/en/latest/) and any other StoryBDD tools available in PHP. This is not an exhaustive list of all available extensions - that's something Google was built for - but rather a list of extensions I have personally used and found useful. Feel free to contribute, my goal is to make the list comprehensive and useful for others, too.

Extensions:
-----------

 - [Behat Step Through](https://github.com/ciaranmcnulty/behat-stepthroughextension) - Helps you debug Behat scenarios by stopping
   execution in between steps
 - [Friends Of Behat](https://github.com/FriendsOfBehat):
	 - PerformanceExtension - Accelerates Behat using features available only for newer PHP versions.
	 - SymfonyExtension - [WIP] Integrates Behat with Symfony (both 2 and 3).
 - [MinkExtension](https://github.com/Behat/MinkExtension) - an abstraction layer that allows Behat to communicate with Selenium and other headless browsers
 - [VersionBasedTestSkipper](https://github.com/ciaranmcnulty/version-based-test-skipper) - Skip Scenarios or Features based on PHP version via annotations
 - [Behat-Screenshot](https://github.com/elvetemedve/behat-screenshot) - Helps you debug Behat scenarios by taking screenshot of the failing steps / scenarios
 - [Behat-BrowserInitialiser](https://github.com/tkotosz/behat-browser-initialiser) - Helps configure the browser for behat scenarios
 - [Behat-StepTimeLogger](https://github.com/tkotosz/behat-step-time-logger) - Helps you find slow behat scenario steps by logging the step times
 - [Behat-Magento2Init](https://github.com/tkotosz/behat-magento2-init) - Provides access to the Magento2 object manager and allows you to change Magento2 config settings temporarly when Behat is running

----------


Why?
----

Mainly because today I was busting my mind trying to remember what was the name of the extension that allowed you to pause a behat instance until you hit enter in the terminal.

Thanks to [Ciaran McNulty](https://twitter.com/CiaranMcNulty/status/786141376945725442) I reached an even better version of what I know it was possible and then it struck me: let's create a list of all useful Behat resources so that next time I need something, I can easily find it there.

Motivation
----------
Last weekend, I attended BgPHP Conference where [the keynote of Cal Evans](https://joind.in/event/bulgaria-php-2016/groupies-roadies-rockstars) was about defining open source contributors in 3 main roles:

 - groupies
 - roadies
 - rockstars

I have [openly admitted](https://twitter.com/GabiUdrescu/status/785124150914453504) then of being a groupie of Sylius. Now I thought of applying for the same statue for Behat. Because... why not?
