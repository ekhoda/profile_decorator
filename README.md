# Profile Decorator
A decorator to profile the run time of functions/classes/modules along with an example to show its usage.

The profile decorator doesn't print the results in `stdout`. Instead, the results are sent to a file. The decorator accepts the following keyword arguments:
1. `output_file` (optional, default = `None`): path of the output file. If not given, the name of the decorated function is used.
2. `sort_by` (optional, default = `'cumulative'`): sorting criteria that can be a `str`, `SortKey` enum, or a tuple/list of those.
3. `lines_to_print` (optional, default = `None`): number of lines to print. If `None` all the lines are printed.
4. `strip_dirs` (optional, default = `False`): whether to remove the leading path info from file names.
