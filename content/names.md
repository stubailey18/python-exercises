# Names/Variables

[<< Back](../README.md)

*Technically they're names, not variables. Python doesn't really have variables in the C/C++ sense of the word.*

I'd recommend you write your code in a file named `names.py`. Alternatively you could use Python in REPL mode.

1. Have Python store in memory the name of the capital city of the UK so that it is accessible using the name `uk_capital`.<details>
    <summary>Show me</summary>

    ```python
    uk_capital = "London"
    ```

</details>

2. Have Python store in memory the approx. UK population so that it is accessible using the name `uk_population`.<details>
    <summary>Show me</summary>

    ```python
    uk_population = 67_000_000
    ```

</details>

3. Have Python store in memory some data indicating whether or not the UK is in NATO so that it is accessible using the name `uk_in_nato`.<details>
    <summary>Show me</summary>

    ```python
    uk_in_nato = True
    ```

</details>

4. Have Python store in memory the name of a team sport commonly played in the UK and elsewhere. Make the data accessible using a name of your choosing.<details>
    <summary>Show me</summary>

    ```python
    sport = "Cricket"
    ```

</details>

5. Have Python store in memory the current US-UK exchange rate. Make the data accessible using a name of your choosing.<details>
    <summary>Show me</summary>

    ```python
    # correct as at 30/01/2024
    us_to_uk_exchange_rate = 0.79
    ```

</details>

6. Have Python store in memory some data indicating that the light is off. Make the data accessible using a name of your choosing.<details>
    <summary>Show me</summary>

    ```python
    light_is_on = False
    ```

</details>

7. Which part of the following statement is the **assignment operator**?
    `email = "geoff@mail.com"`<details>
    <summary>Show me</summary>

    `=`

</details>

8. Which part of the following statement is the **name**?
    `out_on_loan = True`<details>
    <summary>Show me</summary>

    `out_on_loan`

</details>

9. Which part of the following statement is the **integer literal** (the data)?
    `num_steps = 24`<details>
    <summary>Show me</summary>

    `24`

</details>

10. How does one distinguish **data** from a **name** for some data stored in memory?<details>
    <summary>Tell me</summary>

    Data (AKA a literal):
    - is surrounded by quotes (a string literal/text), e.g. `"Hello"`
    - begins with a digit (an integer or floating point number), e.g. `4.5`
    - is the keywords `True` and `False` (a boolean)
    - is surrounded by square brackets/curly braces (a list/dict), e.g. `[1, 2, 3]` or `{x: 0, y: 0}`<br /><br />

    A name for some data stored in memory is a series of characters that is *not* surrounded by quotes and does not begin with a digit, e.g. `coordinates`. Ideally names would always be meaningful words or series of words but, alas, it's common for names to be cryptic, e.g. `dis`.

</details>

11. Which of these is NOT a valid string literal: `"Hello"`, `Hello`, or `'Hello'`?<details>
    <summary>Tell me</summary>

    `Hello` is a name, not a string literal.

</details>

12. The following four tasks are related.

    1. Have Python store in memory the name of the UK's governing party so that it is accessible using the name `uk_governing_party`.<details>
        <summary>Show me</summary>

        ```python
        # correct as at 30/01/2024
        uk_governing_party = "Conservative"
        ```

    </details>

    2. Write to stdout the value associated with the name `uk_governing_party`.<details>
        <summary>Show me</summary>

        ```python
        print(uk_governing_party)
        ```

    </details>

    3. Reassign the name `uk_governing_party` so that it points to the name of the UK's *other* main political party.<details>
        <summary>Show me</summary>

        ```python
        # correct as at 30/01/2024
        uk_governing_party = "Labour"
        ```

    </details>

    4. Repeat step ii.<details>
        <summary>Show me</summary>

        ```python
        print(uk_governing_party)
        ```

    </details>

[<< Back](../README.md)