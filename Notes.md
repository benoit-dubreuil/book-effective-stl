# Notes

- Beware the illusion of container-independent code.
- Prefer range member functions to their single-element counterparts.
	- Range member functions are easier to write.
	- They express your intent more clearly.
	- They exhibit higher performance.
- If you perform any in-place modifications of associative container elements, you are responsible for making sure that the container remains sorted.
