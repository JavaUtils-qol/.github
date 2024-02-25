# JavaUtils-qol

## Conventions:
<ul>
    <li> Every Util must have only static <code>methods</code>/<code>instance variables</code>
    <li> Every <code>instance variable</code> in a Util must be private but can have <code>getters</code>/<code>setters</code>
    <li> Every Util must have a <code>Test.java</code> file.
    <li> Every <code>Test.java</code> file must include an example of every <code>method</code> in the Util.
    <li>Every Util with configuration included must have at least:
    <ul>
        <li>an <code>public static enum</code> of possible configurations
        <li>a <code>private static Config _config</code> variable
        <li>a <code>setter</code>
        <li>a <code>getter</code>
    </ul>
    <li> Every Util must have a <code>private constructor</code>
    <li> Every <code>private method</code> in a Util must be at the bottom of the class (5 lines breaks to separate them)
    <li> Every Util must have <code>javadoc</code> for every <code>public method</code>
</ul>