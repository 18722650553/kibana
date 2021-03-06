<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-plugins-expressions-public](./kibana-plugin-plugins-expressions-public.md) &gt; [Executor](./kibana-plugin-plugins-expressions-public.executor.md) &gt; [createExecution](./kibana-plugin-plugins-expressions-public.executor.createexecution.md)

## Executor.createExecution() method

<b>Signature:</b>

```typescript
createExecution<ExtraContext extends Record<string, unknown> = Record<string, unknown>, Input = unknown, Output = unknown>(ast: string | ExpressionAstExpression, context?: ExtraContext, { debug }?: ExpressionExecOptions): Execution<Context & ExtraContext, Input, Output>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  ast | <code>string &#124; ExpressionAstExpression</code> |  |
|  context | <code>ExtraContext</code> |  |
|  { debug } | <code>ExpressionExecOptions</code> |  |

<b>Returns:</b>

`Execution<Context & ExtraContext, Input, Output>`

