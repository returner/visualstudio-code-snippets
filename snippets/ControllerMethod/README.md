## get
```c#
   /// <summary>
    ///
    /// <summary>
    /// <returns></returns>
    [HttpGet()]
    [SwaggerResponse(200, "success", typeof(IResponseBase))]
    public async Task<IActionResult> GetMethodNameAsync()
    {
        try
        {
            await Task.CompletedTask;
            return new IResponseBase().Ok();
        }
        catch (Exception ex)
        {
            return ex.BadRequest(_logger);
        
```

## pos
```c#
    /// <summary>
    ///
    /// <summary>
    /// <returns></returns>
    [HttpPost()]
    [SwaggerResponse(200, "success", typeof(IResponseBase))]
    public async Task<IActionResult> GetMethodNameAsync()
    {
        try
        {
            await Task.CompletedTask;
            return new IResponseBase().Ok();
        }
        catch (Exception ex)
        {
            return ex.BadRequest(_logger);
        }
    }
```