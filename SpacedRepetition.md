# Spaced Repetition

Spaced repetition is a powerful technique for maximizing recall. For a good overview of simple but effective spaced repetition systems, see this [article](https://collegeinfogeek.com/spaced-repetition-memory-technique/).

In BookThinkers, we use a simple strategy based on buckets. Each bucket is associated with a particular review interval. 
If a user reports remembering the key points from a book, we move it to the next bucket (i.e. notify them to review it less frequently). If they have forgotten, we move it to the previous bucket.

The review frequencies for each bucket are as follows:

- Bucket 1: 1 week
- Bucket 2: 2 weeks
- Bucket 3: 4 weeks
- Bucket 4: 12 weeks
- Bucket 5: 52 weeks (1 year)

# Future Work

## Granularity

In the initial version, we remind users to review whole books. In the future, we may want a more granular approach, 
tracking their retention of each individual note.

## Repetition intervals

Spaced Repetition research typically focuses on small, focused ideas like individual vocabulary words, but our users are remembering broad concepts. 
That means we'll need to fine tune the repetition intervals for our use case. 
