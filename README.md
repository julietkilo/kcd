# kcd
An open format to describe communication relationships in Controller Area Networks (CAN).

## Overview

The KCD format was created because most CAN databases are stored in proprietary formats that are not documented and can not be used for free.
The open source CAN analysis tool [**Kayak**](https://github.com/dschanoeh/Kayak/ "Kayak is an application for CAN bus diagnosis and monitoring") introduced a new and well documented XML based format: KCD (file suffix .kcd). KCD is the acronym for Kayak CAN definition.

The KCD file format has the Lesser GPL license, and is copyrighted by Jan-Niklas Meier (dschanoeh) and Jens Krueger (julietkilo). According to the authors this does not imply any licensing restrictions on software libraries implementing the KCD file format, or on software using those libraries.

Location of the original KCD schema in XSD format
https://github.com/dschanoeh/Kayak/blob/master/Kayak-kcd/src/main/resources/com/github/kayak/canio/kcd/loader/Definition.xsd

Projects using this format:
<table>
    <tr>
        <td>Kayak</td><td>https://github.com/dschanoeh/Kayak</td>
    </tr>
</table>
