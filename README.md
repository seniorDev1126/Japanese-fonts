# Japanese-fonts for generating pdf on laravel project
1. Copy one font of them to storage/fonts in laravel project
2. Add font style to pdf_generate.blade.php file

      @font-face{
          font-family: ipag;
          font-style: normal;
          font-weight: normal;
          src:url('{{ storage_path('fonts/ipag.ttf')}}');
      }
      
      body {
          font-family: ipag;
      }
