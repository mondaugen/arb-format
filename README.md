To format whole file add this to vimrc

    " clang-format entire file
    function FormatFile()
        let l:lines="all"
        pyf /usr/local/share/clang/clang-format.py
    endfunction
    nmap ,ff :call FormatFile()<CR>

Thank you.
