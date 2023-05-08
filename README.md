# Django-Tutorial


This is a template for a Django app. It includes the basic structure and files needed to get started with a new Django app.

## Installation

1. Clone the repository:

```https://github.com/AchrafGazzeh/Django-Tutorial```

2. Run the migrations:

```python manage.py migrate```

3. Start the development server:

```python manage.py runserver```

## Usage

### Index View

The `IndexView` displays a list of the latest five published questions. To access this view, go to `/polls/`.

### Detail View

The `DetailView` displays the details of a specific question. To access this view, go to `/polls/<question_id>/`, where `<question_id>` is the ID of the question you want to view.

### Results View

The `ResultsView` displays the results of a specific question. To access this view, go to `/polls/<question_id>/results/`, where `<question_id>` is the ID of the question you want to view the results for.

### Vote View

The `vote` function handles the voting logic for a specific question. To vote on a question, go to `/polls/<question_id>/vote/`, where `<question_id>` is the ID of the question you want to vote on. Select a choice and click the "Vote" button to submit your vote.
