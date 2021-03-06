# Programming as Conversation Part 3: Introduction

## Learning Goals

* Define abstraction

## Introduction

Before we jump into more code, let's think for a moment about something you
encounter pretty much every day when you read a news article or email: the way
we organize words to express and clarify meaning. For example, a **paragraph**
is a collection of sentences, aligned by a topic sentence and bundled up or
closed by a closing sentence. A **paragraph** can persuade or offend, direct, or
explain. A paragraph has a _function_.

"Code paragraphs" are called, depending on language, "functions," "procedures,"
"methods," or "subroutines." They bundle up expressions and statements to
accomplish a task. Just as "Make a Sandwich" encompasses specific, "atomic"
actions like like "get slice of bread," "get jelly," etc.,
`retrieve_avatar_image_for_user` encompasses logic like `if user_name == nil`
or `if image_url == nil`.

To have code that is easy to read, debug, and maintain, we need to bundle
collections of atomic activities into "code paragraphs" that do work. Ruby
calls these "methods."

## Abstraction

This process of bundling up small atoms into a _method_ is called
"abstraction." "Abstraction" comes from the Latin word for "to pull away." When
we're further away, many details are hard to see. Only the most relevant
shapes are recognizable. For example, when you're on an airplane and are
over a city the details of the mileage, what's in the cup holder, the make, or
the model of the cars below are invisible, they're not _essential_. What is is
the color of the little dots moving up and down the freeway. By abstracting we
see what's more true _generally_.

Here's a few more "abstractions:"

* "Matt," "Lore," and "Mohawk" are atomic individuals, but we can refer to them
  all collectively by the abstraction, or they can be _abstracted_ into "New
  Yorkers"
* Books about a killer dog, a scary alter ego, and a scary clown can be
  _abstracted_ into the name "horror novels (by Stephen King)"
* Individuals with strange powers and (usually) strange clothing can be
  _abstracted_ into "superheroes"

Abstraction is a natural part of learning to converse. When you're first
learning to communicate, you don't know enough to start talking about
abstractions. You prefer to think about real, visible, tangible things. But as
you learn about opposites, how things are similar (and how perhaps one thing is
dissimilar) you grow in your ability to _abstract_.

In fact, the thing that makes most higher learning "higher" is that the
discussion, work, and discovery is focused on uncovering general principles
that allow us to predict how things will work more-or-less most of the time.
Amazingly, this was considered a pretty revolutionary idea at the time when
Galileo and Newton started doing it. The moment that natural philosophers
started looking for these "general rules of how things work," science as we
know it was born.

## Next Steps

Ruby calls bundles of statements that, together, accomplish a unit of work or
process, ***methods***. In Programming as Conversation 3 we'll learn to take
our _expressions_ and _statements_ and bundle them up into abstractions called
_methods_.
