Retrofit

A class may not implement more than one Callback. Yet in some compilation units the requirement is to use Callbacks where two or perhaps more response body types are used. An example would be the need to retrieve a list of residences and to delete a particular residence. Here we examine two patterns to deal with this situation: in one we use inner classes, in the other anonymous classes.