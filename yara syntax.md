~~~
rule <rule Name>
{
  meta:
    // Stores arbitrary key-value pairs of rule details, such as who wrote
    // it, what it detects on, version control, etc.

  events:
    // Conditions to filter events and the relationship between events.

  match:
    // Values to return when matches are found.

  outcome:
    // Additional information extracted from each detection.

  condition:
    // Condition to check events and the variables used to find matches.

  options:
    // Options to turn on or off while executing this rule.
}
~~~