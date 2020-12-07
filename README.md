# scrollbar


```css


    body::-webkit-scrollbar {
        width: 0.25rem;
    }
    body::-webkit-scrollbar-track {
        background: white;
    } 
    body::-webkit-scrollbar-thumb {
        background: #0b052f;
    }




_____________________________________________________________________




    /* The emerging W3C standard
       that is currently Firefox-only */
    * {
      scrollbar-width: thin;
      scrollbar-color: rgba(155, 155, 155, 0.7) transparent;
    }



    /* Works on Chrome/Edge/Safari */
    *::-webkit-scrollbar {
      width: 5px;
    }
    *::-webkit-scrollbar-track {
      background: transparent;
    }
    *::-webkit-scrollbar-thumb {
      background-color: rgba(155, 155, 155, 0.7);
      border-radius: 20px;
      border: transparent;
    }




______________________________________________________________________




    .library {
        overflow-y: scroll;
    }
    .library::-webkit-scrollbar {
        width: 0.25rem;
    }
    .library::-webkit-scrollbar-track {
        background: lavender;
    } 
    .library::-webkit-scrollbar-thumb {
        background: cornflowerblue;
    }



```



___
