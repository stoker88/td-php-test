# PHP Lumen Test

This is a PHP test that will help show your knowledge with creating APIs and dealing with videos.

# The Task

Your task is to create a simple API application using Lumen. The API should have a single endpoint, but should be written with future endpoints in mind. 

The endpoint you must implement should do as follows: 

1. Only accept ``POST`` requests.
2. Be versioned (How you version the API is up to you).
3. Recieve a video file (via multipart/form-data), which should be saved locally. 
4. Use ``getID3`` to process the ``video`` file.
5. Return the analyzed data from ``getID3`` as JSON.

# Considerations

When writing your application, you should consider the following.

1. Make sure you are following the SOLID princles.
2. Make sure your following styling standards like PSR-2.
3. Use TDD to help you write clean and testable code.

# Help

1. https://github.com/JamesHeinrich/getID3
2. https://lumen.laravel.com/docs/5.2
3. https://lumen.laravel.com/docs/5.2/responses#json-responses
4. https://lumen.laravel.com/docs/5.2/requests#files
5. https://github.com/JamesHeinrich/getID3/blob/master/structure.txt
6. https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
