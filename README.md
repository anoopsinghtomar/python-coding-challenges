# Python coding Problem-Solving & challenges

# Project Structure

```text
code-with-python/
│
├── README.md
├── PYTHON_LEARNING_ROADMAP.md
├── PROGRESS_TRACKER.md
├── PROJECT_STRUCTURE.md
├── requirements.txt
├── .gitignore
│
├── phase_01_fundamentals/
│   │
│   ├── basics_part_1/
│   │   ├── 001_variables.py
│   │   ├── 002_data_types.py
│   │   ├── 003_type_conversion.py
│   │   ├── 004_input_output.py
│   │   ├── 005_operators.py
│   │   ├── 006_numbers.py
│   │   ├── 007_strings_basic.py
│   │   └── notes.md
│   │
│   ├── basics_part_2/
│   │   ├── 001_advanced_strings.py
│   │   ├── 002_collections_intro.py
│   │   ├── 003_mutable_immutable.py
│   │   └── notes.md
│   │
│   ├── python_puzzles/
│   │   ├── puzzle_001.py
│   │   ├── puzzle_002.py
│   │   └── puzzle_003.py
│   │
│   └── mastering_python/
│       ├── practice_001.py
│       └── practice_002.py
│
├── phase_02_control_flow/
│
│   ├── conditionals/
│   │   ├── 001_if_statement.py
│   │   ├── 002_if_else.py
│   │   ├── 003_if_elif_else.py
│   │   └── nested_conditions.py
│   │
│   ├── loops/
│   │   ├── 001_for_loop.py
│   │   ├── 002_while_loop.py
│   │   ├── 003_break_continue.py
│   │   └── 004_loop_examples.py
│   │
│   ├── pattern_programs/
│   │   ├── star_pattern.py
│   │   ├── number_pattern.py
│   │   └── pyramid_pattern.py
│   │
│   └── recursion/
│       ├── factorial_recursion.py
│       ├── fibonacci_recursion.py
│       └── recursive_search.py
│
├── phase_03_functions/
│
│   ├── functions/
│   │   ├── function_basics.py
│   │   ├── function_arguments.py
│   │   ├── default_arguments.py
│   │   └── scope_examples.py
│   │
│   ├── lambda/
│   │   ├── lambda_basics.py
│   │   └── lambda_examples.py
│   │
│   ├── map/
│   │   └── map_examples.py
│   │
│   ├── filter/
│   │   └── filter_examples.py
│   │
│   └── itertools/
│       ├── combinations.py
│       ├── permutations.py
│       └── product.py
│
├── phase_04_data_types/
│
│   ├── strings/
│   │   ├── string_001.py
│   │   ├── string_002.py
│   │   └── string_notes.md
│   │
│   ├── lists/
│   │   ├── list_001.py
│   │   ├── list_002.py
│   │   └── list_notes.md
│   │
│   ├── dictionaries/
│   │   ├── dict_001.py
│   │   ├── dict_002.py
│   │   └── dict_notes.md
│   │
│   ├── tuples/
│   │   ├── tuple_001.py
│   │   └── tuple_examples.py
│   │
│   ├── sets/
│   │   ├── set_operations.py
│   │   └── set_examples.py
│   │
│   ├── collections/
│   │   ├── counter_examples.py
│   │   ├── deque_examples.py
│   │   └── defaultdict_examples.py
│   │
│   ├── json/
│   │   ├── read_json.py
│   │   └── write_json.py
│   │
│   └── enum/
│       └── enum_examples.py
│
├── phase_05_oop/
│
│   ├── classes/
│   │   ├── class_basics.py
│   │   ├── constructors.py
│   │   └── methods.py
│   │
│   ├── oop/
│   │   ├── inheritance.py
│   │   ├── polymorphism.py
│   │   ├── encapsulation.py
│   │   └── abstraction.py
│   │
│   └── decorators/
│       ├── function_decorator.py
│       └── class_decorator.py
│
├── phase_06_file_handling/
│
│   ├── file_io/
│   │   ├── read_file.py
│   │   ├── write_file.py
│   │   └── append_file.py
│   │
│   └── csv/
│       ├── read_csv.py
│       └── write_csv.py
│
├── phase_07_exceptions_testing/
│
│   ├── exception_handling/
│   │   ├── try_except.py
│   │   ├── custom_exception.py
│   │   └── raise_exception.py
│   │
│   └── unit_testing/
│       ├── test_functions.py
│       └── test_classes.py
│
├── phase_08_datetime_regex/
│
│   ├── datetime/
│   │   ├── date_examples.py
│   │   └── time_examples.py
│   │
│   └── regular_expressions/
│       ├── regex_basics.py
│       └── regex_validation.py
│
├── phase_09_algorithms_dsa/
│
│   ├── searching/
│   │   ├── linear_search.py
│   │   └── binary_search.py
│   │
│   ├── sorting/
│   │   ├── bubble_sort.py
│   │   ├── selection_sort.py
│   │   ├── insertion_sort.py
│   │   ├── merge_sort.py
│   │   └── quick_sort.py
│   │
│   ├── linked_list/
│   │   ├── singly_linked_list.py
│   │   └── doubly_linked_list.py
│   │
│   ├── tree/
│   │   ├── binary_tree.py
│   │   └── bst.py
│   │
│   ├── heap/
│   │   └── heap_operations.py
│   │
│   └── graphs/
│       ├── bfs.py
│       └── dfs.py
│
├── phase_10_advanced_python/
│
│   ├── generators/
│   │   └── generator_examples.py
│   │
│   ├── multithreading/
│   │   └── threading_examples.py
│   │
│   ├── asyncio/
│   │   └── async_examples.py
│   │
│   └── built_in_modules/
│       ├── os_examples.py
│       ├── sys_examples.py
│       └── pathlib_examples.py
│
├── phase_11_database_api/
│
│   ├── requests/
│   │   ├── get_request.py
│   │   └── post_request.py
│   │
│   ├── sqlite/
│   │   ├── create_database.py
│   │   ├── insert_data.py
│   │   └── crud_operations.py
│   │
│   └── sqlalchemy/
│       └── orm_basics.py
│
├── phase_12_web_scraping/
│
│   ├── beautifulsoup/
│   │   └── scrape_html.py
│   │
│   └── web_scraping/
│       └── scraper_project.py
│
├── phase_13_gui/
│
│   ├── tkinter_basics/
│   │   ├── window.py
│   │   └── button_label.py
│   │
│   └── widgets/
│       └── form_application.py
│
├── phase_14_projects/
│
│   ├── beginner_projects/
│   │   ├── calculator/
│   │   │   └── main.py
│   │   ├── password_generator/
│   │   │   └── main.py
│   │   └── todo_app/
│   │       └── main.py
│   │
│   ├── intermediate_projects/
│   │   ├── expense_tracker/
│   │   │   └── main.py
│   │   └── contact_book/
│   │       └── main.py
│   │
│   └── advanced_projects/
│       ├── weather_app/
│       │   └── main.py
│       └── flask_app/
│           └── app.py
│
├── interview_questions/
│   ├── python_questions.md
│   ├── dsa_questions.md
│   └── oop_questions.md
│
├── notes/
│   ├── python_notes.md
│   ├── dsa_notes.md
│   └── interview_notes.md
│
└── tests/
    ├── test_algorithms.py
    └── test_projects.py
```






