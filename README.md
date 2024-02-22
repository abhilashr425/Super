# Super
@page "/counter"  &lt;h1>Counter&lt;/h1>  &lt;p>Current count: @currentCount&lt;/p>  &lt;button class="btn btn-primary" @onclick="IncrementCount">Click me&lt;/button>  @code {     private int currentCount = 0;      private void IncrementCount()     {         currentCount++;     } }
