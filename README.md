env_set_attribute
=================

Chef plugin to set environment specific attribute

You can run it as:

knife env_set_attr [default/override] [ENVIRONMENT] [ATTRIBUTE]('.' separated) [VALUE]

ATTRIBUTE Hierarchy needs to be separated by dots. Example:
If you want the attribute hierarchy to be :
['abc']['def']['foo'] = 10

you need to run this as:

knife env_set_attr default <Name of environment> abc.def.foo 10
