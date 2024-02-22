[<- Back](../README.md)

# C++11
**C++11** is `the second major version` of C++ and the most important update since **C++98**. A large number of changes were `introduced to both standardize existing practices and improve the abstractions` available to the C++ programmers.

Before it was finally `approved by ISO` on 12 August 2011, the name **C++0x** was used because it was expected to be published **before 2010**. It took 8 years **between C++03 and C++11**, so it has become the longest interval between versions so far. Since then, currently, `C++ updates every 3 years regularly`.

Following features were merged into C++11:
* From TR1: all of TR1 except `Special Functions`
* From Boost: The thread library, exception_ptr, error_code and error_condition, iterator improvements (begin, end, next, prev)

## Core Language Features
* `auto` and `decltype`
* `defaulted` and `deleted` functions
* `final` and `override`
* `trailing return type`
* `rvalue references`
* `move constructors` and `move assignment operators`
* `scoped enums`
* `constexpr` and `literal types`
* `list initialization`
* `delegating` and `inherited constructors`
* brace-or-equal `initializers`
* `nullptr`
* `long long`
* `char16_t` and `char32_t`
* `type aliases`
* `variadic templates`
* `generalized (non-trivial) unions`
* `generalized PODs (trivial types and standard-layout types)`
* `Unicode string literals`
* `user-defined literals`
* `attributes`
* `lambda expressions`
* `noexcept` specifier and `noexcept` operator
* `alignof` and `alignas`
* multithreaded `memory model`
* `thread-local storage`
* `GC interface` *(removed in C++23)*
* `range-for` *(based on a Boost library)*
* `static_assert` *(based on a Boost library)*

## Library features
### Headers

|  Header   | Description   |
| :-------- | :------------ |
| [`<array>`](headers/array.md) | |
| [`<atomic>`](headers/atomic.md) | |
| [`<cfenv>`](headers/cfenv.md) | |
| [`<chrono>`](headers/chrono.md) | |
| [`<cinttypes>`](headers/cinttypes.md) | |
| [`<complex>`](headers/complex.md) | |
| [`<condition_variable>`](headers/condition_variable.md) | |
| [`<cstdint>`](headers/cstdint.md) | |
| [`<cuchar>`](headers/cuchar.md) | |
| [`<forward_list>`](headers/forward_list.md) | |
| [`<future>`](headers/future.md) | |
| [`<initializer_list>`](headers/initializer_list.md) | |
| [`<mutex>`](headers/mutex.md) | |
| [`<random>`](headers/random.md) | |
| [`<ratio>`](headers/ratio.md) | |
| [`<regex>`](headers/regex.md) | |
| [`<scoped_allocator>`](headers/scoped_allocator.md) | |
| [`<system_error>`](headers/system_error.md) | |
| [`<thread>`](headers/thread.md) | |
| [`<tuple>`](headers/tuple.md) | |
| [`<typeindex>`](headers/typeindex.md) | |
| [`<type_traits>`](headers/type_traits.md) | |
| [`<unordered_map>`](headers/unordered_map.md) | |
| [`<unordered_set>`](headers/unordered_set.md) | |

### Library Features

* concurrency support library
* emplace() and other use of rvalue references throughout all parts of the * existing library
* std::unique_ptr
* std::move_iterator
* std::initializer_list
* stateful and scoped allocators
* std::forward_list
* chrono library
* ratio library
* new algorithms:
    * std::all_of, std::any_of, std::none_of,
    * std::find_if_not,
    * std::copy_if, std::copy_n,
    * std::move, std::move_backward,
    * std::random_shuffle, std::shuffle,
    * std::is_partitioned, std::partition_copy, std::partition_point,
    * std::is_sorted, std::is_sorted_until,
    * std::is_heap, std::is_heap_until,
    * std::minmax, std::minmax_element,
    * std::is_permutation,
    * std::iota,
    * std::uninitialized_copy_n
* Unicode conversion facets
* std::function
* std::exception_ptr
* std::error_code and std::error_condition
* iterator improvements:
    * std::begin
    * std::end
    * std::next
    * std::prev
* Unicode conversion functions
