## Option 2
I extended host.go to include the minify parameter. This parameter is used to truncate some larger fields if true. 

To do this, I updated host.go


## Additonal Remarks
I worked on option 1 for a bit, creating a file for dns/resolve, but golang doesn't support varaible field tags in structs. This would be important in order to decode the https.response. 