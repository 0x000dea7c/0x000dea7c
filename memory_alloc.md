# Quick notes about memory allocation techniques

## Resources

- https://www.gingerbill.org/article/2019/02/01/memory-allocation-strategies-001/

## Types of allocations

- Permanent: memory that will only get freed when the program ends.
- Transient: memory with a frame-based or cycle lifetime.
- Scratch: memory that is used for quick and temporary operations like writing a log to a file.

## Allocators

- Linear/arenas: very simple ones. Allocate big chunk upfront and every time I need a chunk from that arena I call arena_alloc (or a similar function), which modifies an offset and returns the new address in O(1).
