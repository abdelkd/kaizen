Sometimes, caching decisions may be unclear and we would need to gather more data to have clear 
understanding and be able to make decisions, for this, I want to make this utility that records 
function calls timings so that after gathering more data I would be able to know which decision 
is better.

The ideal utility should have easy to use functions with less changes, for that the following 
functions are exposed:

  - **createRecorder(upstashInstance)**: This would take the upstash instance as an argument 
  and provide tools to use, the tools are the following:
      - **recordSingle(name: string, fn: (args: ...unknown[]) => unknown):** this would record 
      the function call and returns the result of it
      - **recordMix(name: string, fn1, fn2)** Similar to *recordSingle* but it would record two 
      functions so that the results for both would be made


Under the hood the class Recorder would batch the results and make function calls
