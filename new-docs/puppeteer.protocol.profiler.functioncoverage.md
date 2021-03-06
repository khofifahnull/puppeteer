<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Profiler](./puppeteer.protocol.profiler.md) &gt; [FunctionCoverage](./puppeteer.protocol.profiler.functioncoverage.md)

## Protocol.Profiler.FunctionCoverage interface

Coverage data for a JavaScript function.

<b>Signature:</b>

```typescript
export interface FunctionCoverage 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [functionName](./puppeteer.protocol.profiler.functioncoverage.functionname.md) | string | JavaScript function name. |
|  [isBlockCoverage](./puppeteer.protocol.profiler.functioncoverage.isblockcoverage.md) | boolean | Whether coverage data for this function has block granularity. |
|  [ranges](./puppeteer.protocol.profiler.functioncoverage.ranges.md) | [CoverageRange](./puppeteer.protocol.profiler.coveragerange.md)<!-- -->\[\] | Source ranges inside the function with coverage data. |

