# TinyURL_CS


Package for creating shorted URLs in TinyURL based on C#

This package is free to use for anyone

# How to use it

1. Add the reference librery 'TinyURL_CS.dll' to your project

2. Import the reference 'using TinyURL_CS;'

3. The function 'TinyURLShorter.URLValidator("Url2Short")' takes the long Url and returns a converted the long url that you want to short.

4. The function 'TinyURLShorter.MakeTinyUrl("longUrl")' takes the converted long url and returns the shorted url form TinyUrl.

# Example

private string shorter(string url2short)
{
       String longUrl = TinyURLShorter.URLValidator(url2short);
       String shortUrl = TinyURLShorter.MakeTinyUrl(longUrl);
       return shortUrl;
}
