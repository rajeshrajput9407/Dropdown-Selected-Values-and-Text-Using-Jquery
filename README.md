# Dropdown-Selected-Values-and-Text-Using-Jquery
# User can Get Text() and Val() and User Can do  Selected dropdown from multiples values


var val =$("#Country option:selected").val();
var text =$("#Country option:selected").text();

 $("#Country option[text='US']").attr("selected", "selected");
                debugger;
                var defaultVal = "US";
                $("#Country").find("option").each(function () {

                   if ($(this).val() == defaultVal) {
                          $(this).prop("selected", "selected");
                   }
                    
                    if ($(this).text() == defaultVal) {

                        $(this).prop("selected", "selected");
                    }
                });
