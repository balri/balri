<html>
    <head>
        <script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
    </head>
    <body>
        <textarea cols="60" id="source"></textarea>
        GGWWGGBGGGGWWBBWWWWWWWBGBWBWWW
        <br /><br />
        B: <input type="number" id="black" value="0" />
        G: <input type="number" id="grey" value="1" />
        W: <input type="number" id="white" value="2" />
        <br /><br />
        <textarea cols="60" id="ternary"></textarea>
        <br /><br />
        3: <input type="number" id="ternaryLen" value="3" />
        0: <input type="number" id="ternaryLeading" value="0" />
        <br /><br />
        <textarea cols="60" id="ternarySplit"></textarea>
        <br /><br />
        <textarea cols="60" id="binary"></textarea>
        <br /><br />
        2: <input type="number" id="binaryLen" value="7" />
        0: <input type="number" id="binaryLeading" value="0" />
        <br /><br />
        <textarea cols="60" id="binarySplit"></textarea>
        <br /><br />
        <textarea cols="60" id="decimal"></textarea>
        <br /><br />
        <textarea cols="60" id="text"></textarea>
        <script type="text/javascript">
            $(document).ready(function(){
                $('#source').on('keyup', function() {
                    $('#ternary').val($.trim($(this).val()).replace(/B|b/g, $('#black').val())
                            .replace(/G|g/g, $('#grey').val())
                            .replace(/W|w/g, $('#white').val())).trigger('change');
                });
                $('#black,#grey,#white').on('change', function() {
                    $('#source').trigger('keyup');
                });
                $('#ternary').on('change', function() {
                    var len = parseInt($('#ternaryLen').val());
                    var val = $(this).val().padStart($(this).val().length
                            + parseInt($('#ternaryLeading').val()), '0');
                    $('#ternarySplit').val(val.match(new RegExp('.{1,' + len + '}', 'g'))
                            .join(' ')).trigger('change');
                });
                $('#ternaryLen,#ternaryLeading').on('change', function() {
                    $('#ternary').trigger('change');
                });
                $('#ternarySplit').on('change', function() {
                    var b = '';
                    jQuery.each($(this).val().split(' '), function(k, v) {
                        var i = parseInt(v, 3);
                        b += i.toString(2);
                    });
                    $('#binary').val(b).trigger('change');
                });
                $('#binary').on('change', function() {
                    var len = parseInt($('#binaryLen').val());
                    var val = $(this).val().padStart($(this).val().length
                            + parseInt($('#binaryLeading').val()), '0');
                    $('#binarySplit').val(val.match(new RegExp('.{1,' + len + '}', 'g'))
                            .join(' ')).trigger('change');
                });
                $('#binaryLen,#binaryLeading').on('change', function() {
                    $('#binary').trigger('change');
                });
                $('#binarySplit').on('change', function() {
                    var d = '';
                    jQuery.each($(this).val().split(' '), function(k, v) {
                        var i = parseInt(v, 2);
                        d += i.toString(10) + ' ';
                    });
                    $('#decimal').val(d).trigger('change');
                });
                $('#decimal').on('change', function() {
                    var t = '';
                    jQuery.each($(this).val().split(' '), function(k, v) {
                        t += String.fromCharCode(v);
                    });
                    $('#text').val(t);
                });
            });
        </script>
    </body>
</html>