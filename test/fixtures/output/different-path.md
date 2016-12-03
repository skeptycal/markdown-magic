# Test Fixture

<!-- AUTO-GENERATED-CONTENT:START (CODE:src=./local-code-file.js) - Do not remove or modify this section -->
<!-- The below code snippet is automatically added from ./local-code-file.js -->
```js
module.exports.run = () => {
  const time = new Date()
  console.log(`Your cron ran ${time}`)
}
```
<!-- AUTO-GENERATED-CONTENT:END -->

<!-- AUTO-GENERATED-CONTENT:START (CODE:src=https://raw.githubusercontent.com/segmentio/is-url/master/index.js) - Do not remove or modify this section -->
<!-- The below code snippet is automatically added from https://raw.githubusercontent.com/segmentio/is-url/master/index.js -->
```js
/**
 * Expose `isUrl`.
 */

module.exports = isUrl;

/**
 * Matcher.
 */

var matcher = /^(?:\w+:)?\/\/([^\s\.]+\.\S{2}|localhost[\:?\d]*)\S*$/;

/**
 * Loosely validate a URL `string`.
 *
 * @param {String} string
 * @return {Boolean}
 */

function isUrl(string){
  return matcher.test(string);
}
```
<!-- AUTO-GENERATED-CONTENT:END -->

<!-- AUTO-GENERATED-CONTENT:START (REMOTE:url=https://raw.githubusercontent.com/serverless/community-plugins/master/README.md) - Do not remove or modify this section  -->
[Website](http://www.serverless.com) • [Email Updates](http://eepurl.com/b8dv4P) • [Gitter](https://gitter.im/serverless/serverless) • [Forum](http://forum.serverless.com) • [Meetups](https://github.com/serverless-meetups/main) • [Twitter](https://twitter.com/goserverless) • [Facebook](https://www.facebook.com/serverless) • [Contact Us](mailto:hello@serverless.com)

## Community Plugins

[Serverless Plugins](https://serverless.com/framework/docs/providers/aws/guide/plugins/) allow users to extend or overwrite the framework's core functionality. Many of these plugins are contributed by our amazing community members! 🎉

This repository is meant to be the one stop shop for all the awesome plugins out there in the serverless ecosytem.

If you have ideas for features or plugins, add a new [thread](https://github.com/serverless/community-plugins/issues) in the issues.

## Community Contributed Plugins

### [Add it to the plugin list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

<!-- AUTO-GENERATED-CONTENT:START (GENERATE_PLUGIN_LIST)
- Do not remove or modify this section. Make all updates to plugins.json -->
| Plugin name | description  |
|:--------------------------- |:-----|
| [Serverless Alexa Plugin](https://github.com/rajington/serverless-alexa-plugin) | Serverless plugin to support Alexa Lambda events |
| [Serverless Build Plugin](https://github.com/nfour/serverless-build-plugin) | A Node.js focused build plugin for serverless. |
| [Serverless Command Line Event Args](https://github.com/horike37/serverless-command-line-event-args) | This module is Serverless Framework plugin. Event JSON passes to your Lambda function in commandline. |
| [Serverless Crypt](https://github.com/marcy-terui/serverless-crypt) | Securing the secrets on Serverless Framework by AWS KMS encryption. |
| [Serverless Dynamodb Local](https://github.com/99xt/serverless-dynamodb-local) | Serverless Dynamodb Local Plugin - Allows to run dynamodb locally for serverless |
| [Serverless Event Constant Inputs](https://github.com/dittto/serverless-event-constant-inputs) | Allows you to add constant inputs to events in Serverless 1.0. This is defined in https://aws.amazon.com/blogs/compute/simply-serverless-use-constant-values-in-cloudwatch-event-triggered-lambda-functions/ |
| [Serverless Mocha Plugin](https://github.com/SC5/serverless-mocha-plugin) | A Serverless Plugin for the Serverless Framework which adds support for test driven development using mocha |
| [Serverless Offline](https://github.com/dherault/serverless-offline) | Emulate AWS λ and API Gateway locally when developing your Serverless project |
| [Serverless Plugin Aws Alerts](https://github.com/ACloudGuru/serverless-plugin-aws-alerts) | A Serverless plugin to easily add CloudWatch alarms to functions |
| [Serverless Plugin Browserify](https://github.com/doapp-ryanp/serverless-plugin-browserify) | Speed up your node based lambda's |
| [Serverless Plugin Cfauthorizer](https://github.com/SC5/serverless-plugin-cfauthorizer) | This plugin allows you to define your own API Gateway Authorizers as the Serverless CloudFormation resources and apply them to HTTP endpoints. |
| [Serverless Plugin Cloudwatch Sumologic](https://github.com/ACloudGuru/serverless-plugin-cloudwatch-sumologic) | Plugin which auto-subscribes a log delivery lambda function to lambda log groups created by serverless |
| [Serverless Plugin Diff](https://github.com/nicka/serverless-plugin-diff) | Compares your local AWS CloudFormation templates against deployed ones. |
| [Serverless Plugin External Sns Events](https://github.com/silvermine/serverless-plugin-external-sns-events) | Add ability for functions to use existing or external SNS topics as an event source |
| [Serverless Plugin Include Dependencies](https://github.com/dougmoscrop/serverless-plugin-include-dependencies) | This is a Serverless plugin that should make your deployed functions smaller. |
| [Serverless Plugin Multiple Responses](https://github.com/silvermine/serverless-plugin-multiple-responses) | Enable multiple content-types for Response template  |
| [Serverless Plugin Optimize](https://github.com/FidelLimited/serverless-plugin-optimize) | Bundle with Browserify, transpile with Babel to ES5 and minify with Uglify your Serverless functions. |
| [Serverless Plugin Package Dotenv File](https://github.com/ACloudGuru/serverless-plugin-package-dotenv-file) | A Serverless plugin to copy a .env file into the serverless package |
| [Serverless Plugin Stack Outputs](https://github.com/svdgraaf/serverless-plugin-stack-outputs) | Displays stack outputs for your serverless stacks when `sls info` is ran |
| [Serverless Plugin Stage Variables](https://github.com/svdgraaf/serverless-plugin-stage-variables) | Add stage variables for Serverless 1.x to ApiGateway, so you can use variables in your Lambda's |
| [Serverless Plugin Stage Variables](https://github.com/svdgraaf/serverless-plugin-stage-variables) | Add stage variables for Serverless 1.x to ApiGateway, so you can use variables in your Lambda's |
| [Serverless Plugin Write Env Vars](https://github.com/silvermine/serverless-plugin-write-env-vars) | Write environment variables out to a file that is compatible with dotenv |
| [Serverless Resources Env](https://github.com/rurri/serverless-resources-env) | After Deploy, this plugin fetches cloudformation resource identifiers and sets them on AWS lambdas, and creates local .<state>-env file |
| [Serverless Run Function Plugin](https://github.com/lithin/serverless-run-function-plugin) | Run serverless function locally |
| [Serverless Scriptable Plugin](https://github.com/wei-xu-myob/serverless-scriptable-plugin) | Customize Serverless behavior without writing a plugin. |
| [Serverless Subscription Filter](https://github.com/blackevil245/serverless-subscription-filter) | Serverless plugin to register subscription filter for Lambda logs. Register and pipe the logs of one lambda to another to process. |
| [Serverless Webpack](https://github.com/elastic-coders/serverless-webpack) | Serverless plugin to bundle your lambdas with Webpack |
| [Serverless Wsgi](https://github.com/logandk/serverless-wsgi) | Serverless plugin to deploy WSGI applications (Flask/Django/Pyramid etc.) and bundle Python packages |
<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END - Do not remove or modify this section. Make all updates to plugins.json -->

### [Add your plugin to the list](https://github.com/serverless/community-plugins/edit/master/plugins.json)

After adding your plugin to the `plugins.json` file, run `npm run docs` to regenerate the plugin list table in the `readme.md` file.

<!-- AUTO-GENERATED-CONTENT:END
- Do not remove or modify this section. Make all updates to plugins.json -->

keep this content