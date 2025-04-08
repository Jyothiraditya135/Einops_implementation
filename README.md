# Einops_implementation
An implementation of the functionalities of the einops library written only in numpy.

The code file has the following structure:
- The implementation: All the necessary functions that are called implicitly or explicitly in rearrange()
- A few examples higlighting the basic functionalities of rearrange and showing that it works for split, merge, transpose, repat, their combinations and the ability to handle ellipsis.
- Inspired from the einops tutorial, the 3rd section contains a few bizzare, complex cases taken from the einops tutorial_1.ipynb.
- The 4th section highlights error handling for a few cases, with the rearrange() function handling more of them too.
  
The einops library has been invoked in the implementation in the 2nd section, to check the correctness of the implementation using the logic *np.array_equal(b_x, c_x)*
where
- b_x is the output from the custom rearrange function and
- c_x is the output expected from appropriate einops function called.
