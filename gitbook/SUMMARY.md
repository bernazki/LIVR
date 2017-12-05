# Summary

* [Read Me](README.md)
* [Introduction](introduction.md)
    * [Motivation](introduction/motivation.md)
    * [Core concepts](introduction/core-concepts.md)
    * [Implementations](introduction/implementations.md)
    * [Principles](introduction/principles.md)
    * [Ecosystem](introduction/ecosystem.md)
    * [Examples](introduction/examples.md)
* [Validation Rules](validation-rules.md)
    * [How it works](validation-rules/how-it-works.md)
    * [Types coercing](validation-rules/types-coercing.md)
    * [Common](validation-rules/common-rules.md#common)
        * [required](validation-rules/common-rules.md#required)
        * [not_empty](validation-rules/common-rules.md#not-empty)
        * [not_empty_list](validation-rules/common-rules.md#not-empty-list)
        * [any_object](validation-rules/common-rules.md#any-object)
    * [String](validation-rules/string-rules.md)
        * [string](validation-rules/string-rules.md#string)
        * [eq](validation-rules/string-rules.md#eq)
        * [one_of](validation-rules/string-rules.md#one-of)
        * [max_length](validation-rules/string-rules.md#max-length)
        * [min_length](validation-rules/string-rules.md#min-length)
        * [length_between](validation-rules/string-rules.md#length-between)
        * [length_equal](validation-rules/string-rules.md#length-equal)
        * [like](validation-rules/string-rules.md#like)
    * [Numeric](validation-rules/numeric-rules.md)
        * [integer](validation-rules/numeric-rules.md#integer)
        * [positive_integer](validation-rules/numeric-rules.md#positive-integer)
        * [decimal](validation-rules/numeric-rules.md#decimal)
        * [positive_decimal](validation-rules/numeric-rules.md#positive-decimal)
        * [max_number](validation-rules/numeric-rules.md#max-number)
        * [min_number](validation-rules/numeric-rules.md#min-number)
        * [number_between](validation-rules/numeric-rules.md#number-between)
    * [Special](validation-rules/special-rules.md)
        * [email](validation-rules/special-rules.md#email)
        * [url](validation-rules/special-rules.md#url)
        * [iso_date](validation-rules/special-rules.md#iso-date)
        * [equal_to_field](validation-rules/special-rules.md#equal-to-field)
    * [Metarules](validation-rules/metarules.md)
        * [nested_object](validation-rules/metarules.md#nested-object)
        * [variable_object](validation-rules/metarules.md#variable-object)
        * [list_of](validation-rules/metarules.md#list-of)
        * [list_of_objects](validation-rules/metarules.md#list-of-objects)
        * [list_of_different_objects](validation-rules/metarules.md#list-of-different-objects)
        * [or](validation-rules/metarules.md#or)
    * [Modifiers](validation-rules/modifiers.md)
        * [trim](validation-rules/modifiers.md#trim)
        * [to_lc](validation-rules/modifiers.md#to-lc)
        * [to_uc](validation-rules/modifiers.md#to-uc)
        * [remove](validation-rules/modifiers.md#remove)
        * [leave_only](validation-rules/modifiers.md#leave-only)
        * [default](validation-rules/modifiers.md#default)
* [Rules aliasing](rules-aliasing.md)
* [How to contribute](how-to-contribute.md)
    * [Create own Implementation](how-to-contribute/create-own-implementation.md)
    * [Create own Plugins](how-to-contribute/create-own-plugins.md)
* [Changes](changes.md)
* [License](license-and-copyright.md)