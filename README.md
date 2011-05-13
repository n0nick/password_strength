### jQuery Password Strength

This plugin will check the value of a password field and evaluate the strength of the typed password. This is done by checking for the diversity of character types: numbers, lowercase and uppercase letters and special characters.

To use, call the function on a password field:

<code>
$('input[type=password]').password_strength(options);
</code>

The options argument is optional. Available values to set:

* __container__: Element to display the strength text in. If none given, a span would be created immediately after the password field.

* __minLength__: Minimum password length.

* __texts__: An array of strength texts for the 5 different levels, to override the default texts.

* __onCheck__: A callback that gets called after a strength check. Gets the new strength value as a parameter.

jQuery plugin page: http://plugins.jquery.com/project/password_strength

#### License

The software is provided AS IS under the terms of the [GNU General Public License](http://www.gnu.org/licenses/gpl-3.0.txt).
