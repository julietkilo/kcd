# kcd
An open format to describe communication relationships in Controller Area Networks (CAN).

## Overview

The KCD format was created because most CAN databases are stored in proprietary formats that are not documented and can not be used for free.
The open source CAN analysis tool [**Kayak**](https://github.com/dschanoeh/Kayak/ "Kayak is an application for CAN bus diagnosis and monitoring") introduced a new and well documented XML based format: KCD (file suffix .kcd). KCD is the acronym for Kayak CAN definition.

## Description of the format
The Location of the original KCD schema in XSD format is
https://github.com/dschanoeh/Kayak/blob/master/Kayak-kcd/src/main/resources/com/github/kayak/canio/kcd/loader/Definition.xsd

## Projects

Projects that are using this format:
<table>
    <tr>
        <td>Kayak</td><td>https://github.com/dschanoeh/Kayak</td>
    </tr>
    <tr>
        <td>CANBabel</td><td>https://github.com/julietkilo/CANBabel</td>
    </tr>
    <tr>
        <td>openCanSuite</td><td>https://github.com/sebi2k1/openCanSuite</td>
    </tr>
    <tr>
        <td>Canmatrix Convert Libray and Tool</td><td>https://github.com/ebroecker/canmatrix</td>
    </tr>
</table>

It would be nice to hear from your project. 

## Licence

The files that are describing the format are published under the Lesser GPL license. The KCD format is copyrighted by Jan-Niklas Meier (dschanoeh) and Jens Krueger (julietkilo). According to the authors this does not imply any licensing restrictions on software libraries implementing the KCD file format, or on software using those libraries.
