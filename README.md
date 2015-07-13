# WP-Post-Type-Resolver (Wordpress Plugin)
Wordpress Plugin, which return the `post type` of a given post (usefull for AJAX Requests).


### HTTP `REQUEST`:
```
/post-type-resolver/... + ID
```

###JSON `RESPONSE`:
```
{
	"post_type": "custom-post-type-name"
}
```