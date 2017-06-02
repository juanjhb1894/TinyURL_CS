The TinyURL_CS.dll is the file to use

This is an Example

        private string shorter(string url2short)
        {
            String longUrl = TinyURLShorter.URLValidator(url2short);
            String shortUrl = TinyURLShorter.MakeTinyUrl(longUrl);
            return shortUrl;
        }
