net.sourceforge.dita4publishers.doctypes
========================================

Plugin with catalogs that redirect to the org.dita4publishers.doctypes plugin. Enables D4P 0.9 URNs to be resolved. Documents using these URNs should be migrated to use the new URNs if possible.

The change in the URNs is to replace "net.sourceforge" with "org", changing the
domain part of the URN from "net.sourceforge.dita4publishers.doctypes" to
"org.dita4publishers.doctypes".

There is no change to the vocabulary itself: the tagnames and @class values are
unchanged from version 0.9 to 1.0 of DITA for Publishers.
