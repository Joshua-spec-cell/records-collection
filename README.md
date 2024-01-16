# records-collection
creating a function that aids in the maintenance of a musical album collection. The collection is organized as an object that contains multiple albums which are also objects.
First it checks if the value is an empty string. If it is, then the prop is deleted.
Then, if prop is not "tracks" and the value is not an empty string. The prop is set to the value.
If that check doesn’t pass, it next checks if prop is equal to tracks, the value is not an empty string, and the record does not have a tracks array. The "tracks" array is initialized with the only contents being value.
It next checks if prop is equal to tracks, the value is not an empty string. The "tracks" array must exist because the case above was not true. The value is pushed onto the end of the "tracks" array.
Lastly, the entire records object is returned.
