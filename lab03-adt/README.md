# Lab 3 — Class Design & ADTs
Stack contract: push has no precondition and makes its item top; pop/peek require a non-empty stack; isEmpty reports emptiness; size reports element count. State is private.
Two interchangeable representations are implemented: ArrayStack and LinkedStack. Clients use only Stack<T>, so representation can change without client changes.