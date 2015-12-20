[![SensioLabsInsight](https://insight.sensiolabs.com/projects/9c258ecb-2cb3-4597-8f04-ecb36f5fd76a/mini.png)](https://insight.sensiolabs.com/projects/9c258ecb-2cb3-4597-8f04-ecb36f5fd76a)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/vincentaubert/base-console-app/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/vincentaubert/base-console-app/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/vincentaubert/base-console-app/badges/build.png?b=master)](https://scrutinizer-ci.com/g/vincentaubert/base-console-app/build-status/master)

This is a base to create console applications.

It's based on the Symfony console component and Box to generate phar files automatically.

To build a phar you have to :
- verify that phar.readonly config is set to Off in your php.ini
- run php box.phar build

