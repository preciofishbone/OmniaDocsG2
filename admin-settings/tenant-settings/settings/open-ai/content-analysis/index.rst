Content analysis (OpenAI)
=============================================

This option is available in Omnia 7.1 and later.

You can set up a number of sets for content analysis, to be used by editors. Here's an example:

.. image:: content-analysis.png

Click the pen to edit, the dust bin to delete.

All settings are available for edit, see below.

Create a new analysis
************************
When creating a new analysis, the following settings are available:

.. image:: content-analysis-new.png

+ **Title**: Add a title for this setting, in any available tenant language (click the flag to change language). Mandatory.
+ **Prompt**: Add the text (the instruction to OpenAI) for the prompt here. Note the message under the field. The prompt must contain the token {Text} within quotation marks.
+ **Criteria to pass check**: Can be Yes or No.
+ **Default enterprise properties**: Select one or more properties here.
+ **Prompt fix**: You can add a prompt to ask OpenAI to fix something in the content, for example to fix the spelling.
+ **TRY OUT** You can try out the settings by clicking this button.

Here's an exaple of content analysis prompt:

.. image:: content-analysis-example.png

