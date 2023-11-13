# 0x00. Fix my code

## about

Fix my code is a new type of project, where we’ll jump into an existing code base and fix it!

Sometimes you will know the language, sometimes not.

Please download the repository 0x00-Fix_My_Code_Challenge and use it as initial files for all solutions.

You should not recode everything, just fix it!

## mandatory

0. FizzBuzz:

- change line 19 and `and (i % 5) == 0`
- change line 20 `FizzBuzz`
- change line 22 `Fizz`

1. Print square:

- line 16: change from base 16 (hexadecimal) instead of base 10.

2. Sort:

- change line 23: change `i + 1` = `i`.
- chabge line 25: delete break no need:
  there's no need to use break after inserting.
  you can simply set is_inserted to true.

3. User password:

- line 87: delete not.

4. Double linked list:

- in file Fix_My_Code_Challenge/0x00-challenge/4-delete_dnodeint/delete_dnodeint_at_index.c:
  - line 24: change `(*head)->next != NULL`
    p should't increment when (\*head)->next == NULL => index node dosent exist.
  - line 46: change to `(*head)->prev->next = (*head)->next;` the previous one doesn't make sense
  - line 47: should not free (\*head) before line 48, 49. so i switch it.
