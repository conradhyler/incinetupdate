# InciNet Single User Mode Fix

This batch will solve the issue where InciNet does not work when put into multiuser mode and the default entry of localhost is overwritten.  This will cause an unrecoverable crash upon opening InciNet without a server present on the defined IP address

You will need to add the latest TNSnames.ora file in the directory as a TNSnames.ora.default.
