// Only process the scripts below if the document is ready function
$(document).ready(function () {

// Adding SU Security Footer
var SUSecurity_text = 'NOTICE: UNAUTHORIZED ACCESS to this system is in violation of Md. Annotated Code, Criminal Law Article ASAS 8-606 and 7-302 and the Computer Fraud and Abuse Act, 18 U.S.C. ASAS 1030 et seq. The system is for the use of authorized users only.  Anyone using this system expressly consents to having their use of the system monitored and recorded by system personnel.  If such monitoring reveals possible evidence of criminal activity, system personnel may provide the evidence of such monitoring and recording to law enforcement officials.  By clicking above you are consenting to the <a href="http://www.salisbury.edu/helpdesk/doc/HelpDesk/Policies/Policies_AcceptableUsePolicy.pdf" style="color: #FFD700" target="_blank">Acceptable Use Policy of SU</a>.';
var added_html_and_text2 = '<div class="SUSecurityfooter"><blockquote> ' + SUSecurity_text + '</blockquote></div>';
var added_html_and_text2_mobile = '<div class="SUSecurityfooterMobile"> ' + SUSecurity_text + '</div>';

// Only manipulate the login page 
$('.ic-Login__container').append(added_html_and_text2);
$('#f1_container').append(added_html_and_text2_mobile);

});

// jlkelly - 05/18/2017 - Commented out unmatched brackets
//});

//////////////////////////////////////////////////////////////////////////////
// DESIGN TOOLS CONFIG                                                      //
// Copyright (C) 2016  Utah State University                                //
// Modified for SU on 8/3/2017 by Melissa Thomas                            //
// Modified 11/13/2017 added Academic ID                                    //
// Modified 8/2/2018 to switch to limit by Role instead of by User          //
// Modified 7/18/2020 set hideButton to false, appear for all User by role  //
//////////////////////////////////////////////////////////////////////////////
    var DT_variables = {
            iframeID: '',
            // Path to the hosted USU Design Tools
            path: 'https://designtools.ciditools.com/',
            templateCourse: '19584', // canvas id of customization course
            // OPTIONAL: Limit tools loading by users role
			hideButton: false, // set to true to automatically hide the rocketship
            limitByRole: true, // set to true to limit to roles in the roleArray
            // adjust roles as needed
            roleArray: [
                'admin',
                'teacher',
                'designer'
            ],
            // OPTIONAL: Limit tools to an array of Canvas user IDs
            limitByUser: false, // Change to true to limit by user
            // add users to array (Canvas user ID not SIS user ID)
            userArray: [
                '74', //sssaid
                '90', //mdthomas
				'14304', //hjcristea
            ]
        };

    // Run the necessary code when a page loads
    $(document).ready(function () {
        'use strict';
        // This runs code that looks at each page and determines what controls to create
        $.getScript(DT_variables.path + 'js/master_controls.js', function () {
            console.log('master_controls.js loaded');
        });
    });
////////////////////////////////////////////////////
// END DESIGN TOOLS CONFIG                        //
////////////////////////////////////////////////////