# information-security-systems-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [Information-Security-Systems Assignment 5 Solved](https://www.ankitcodinghub.com/product/information-security-systems-assignment-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98697&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Information-Security-Systems Assignment 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ol start="0">
<li style="list-style-type: none;">
<ol start="0">
<li>Implement a basic ransomware</li>
</ol>
</li>
</ol>
For this assignment, you will develop a basic ransomware. It is a type of malicious software that is used to block access to the files of a user by encrypting them. Its main goal is to extort money from users in order to decrypt their files back. The main functionality of the ransomware is to encrypt a number of files and delete the original unencrypted files. Of course, a proper ransomware would be able to detect the access control logging system and bypass it. However, for the purposes of this assignment, you are required to provide only the basic functionality that we ask for.

Step 1: Implement the ransomware

More specifically, you should develop a bash script (named “ransomware.sh”) that demonstrates the creation, encryption &amp; deletion of a number of files inside a directory in a certain amount of time. More specifically, you should (1) create/select the files to be encrypted, (2) produce the new, encrypted files, and finally (3) delete the original files. We strongly suggest you to create new text files that will then be encrypted. DO NOT RISK encrypting and deleting your existing files that you don’t want to lose/corrupt.

Your ransomware should also be able to create a big volume of files, so given a directory as an argument, it should create X1 files in that directory. X is also given as an argument.

You can use the OpenSSL binaries for the encryption of the files. Two aes-ecb examples follow, make sure you use the correct encryption function as parameter and the correct key. In the following example the encryption password is “1234”.

1 X is an integer number that specifies the number of files your ransomware must create.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Encryption: File deletion: Decryption:

For more information on the OpenSSL command line tool visit:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>$ openssl enc -aes-256-ecb -in test.txt -out test.txt.encrypt -k 1234
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
$ rm test.txt

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>$ openssl aes-256-ecb -in test.txt.encrypt -out test.txt -d -k 1234
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
● https://linux.die.net/man/1/openssl

● https://wiki.openssl.org/index.php/Command_Line_Utilities

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Step 2: Use the Access Control Logging tool from previous assignment2

Your ransomware will make use of the shared library you implemented in the previous assignment “Access Control Logging”, named “logger.so”. This means that every access type (create, open or write) will be logged with an entry in the log file named “file_logging.log”. Therefore, the entries must have the same format as in the previous assignment:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<ol>
<li>UID: The unique user ID assigned by the system to a user (hint: see getuid() function).</li>
<li>File name: The path and name of the accessed file.</li>
<li>Date: The date that the action occurred.</li>
<li>Timestamp: The time that the action occurred.</li>
<li>Access type: For file creation, the access type is “0”. For file open, the access type is “1”. For file write, the access type is “2”.</li>
<li>Is-action-denied flag: This field reports if the action was denied to the user with no access privileges. It is “1” if the action was denied to the user, or “0” otherwise.</li>
<li>File fingerprint: The digital fingerprint of the file the time the event occurred. This digital fingerprint is the hash value of the file contents (hint: You can use the md5 hash functions: https://www.openssl.org/docs/man1.1.0/man3/MD5_Init.html ).</li>
</ol>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Events that must be logged:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1. File creation: Every time a user creates a file, the log file must be updated with information

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
about the creation of the file. Make sure to modify the fopen() function in a way that the

creation of a file can be distinguished from the opening of an existing file.

2. File opening: Every time a user tries to open a file, the log file must be updated with the corresponding file access attempt information. For this case, fopen() functions need to be

intercepted and information about the user and the file access has to be collected.

3. File modification (write): Every time a user tries to modify a file, the log file should be updated with the corresponding file modification attempt information. This means that fwrite() functions need to be intercepted and information about the user and the file access has to be

collected. Every fopen()/fwrite() function should create a new entry in a log file.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2 This step only requires to use the logger.so shared library from assignment 3.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Step 3: Detect the ransomware by enriching the Access Control Log Monitoring tool from Assignment 3

Enrich your Access Control Monitoring tool from the previous assignment, named “acmonitor.c”, to have the following extra functionality. The Access Control Monitoring tool will detect the existence of your ransomware. More specifically:

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1. In many cases, a ransomware tries to hide malicious files in directories populated by huge amounts of files. In this scenario, a ransom will create a big volume of files. You need to find if X files (at minimum) were created in the last 20 minutes.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2. A ransomware will also try to encrypt files and then discard the unencrypted version of those files. You need to find and report all the events in the log where a ransomware opened an unencrypted file and created an encrypted one. Remember that encrypted files have the suffix “.encrypt”.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
Tool Specification

The enriched Access Control Log Monitoring tool (Step 3) will receive the required arguments from the command line upon execution. Specifically, you should add the (1) -v &lt;number of files&gt; and the (2) -e options, and keep the -m, -i, -h options as-is from the previous assignment.

Options

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Prints malicious users

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
-m

<pre>-i &lt;filename&gt;
</pre>
<pre>-v &lt;number of
    files&gt;
</pre>
-e

-h

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Prints table of users that modified the file given and the number of modifications

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Prints the total number of files created in the last 20 minutes

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Prints all the files that were encrypted by the ransomware

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Help message

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Notes

<ol>
<li>If no appropriate option is given, the Access Control Monitoring tool has to print the corresponding error message.</li>
<li>You need to create a Makefile to compile your library and programs (you must submit it with your source code), or, you can use the one provided in the previous related assignment.</li>
<li>We do not provide you with a source code corpus; you have to enrich the source code of the previous related assignment.</li>
<li>You must submit the following files: README, Makefile, logger.c, logger.so, acmonitor.c, ransomware.sh</li>
<li>You need to submit all the source code of your tool, a “Makefile”, and a “README.txt” file that explains briefly your implementation and what you didn’t implement and why. Place all these files in a folder named &lt;yourlastnameAM&gt;_assign5, and then compress it as a .zip file that you will upload to eclass. For example: christodoulou2018123456_assign5.zip.</li>
<li>The README.txt file is important to submit.</li>
<li>Very important: execute the command gcc –-version and write whatever the output is into your
README.txt file, e.g. “gcc (Ubuntu 9.3.0-10ubuntu2~20.04)”
</li>
<li>Your logfile should have a log entry for the creation of files e.g. the “.encrypt” files. But this
cannot be implemented with fopen. Hint: search for fopen64 (o_fopen.c, bss_file.c line 12). Try to implement the fopen64 (it calls the fopen). You might also need to pass the flag -D_FILE_OFFSET_BITS=64 into the makefile that creates the logger.so.
</li>
<li>The entries in the logfile should be created from fopen and fwrite. Do not implement the log entries using bash function. What you can do is: from bash, call a new test_aclog.c file with ./test_aclog, which in turn calls the fopen (therefore the action will be logged), in order to test the Steps 2 and 3. In your submitted files include also the test_aclog.c.</li>
<li>In the script for ransomware, as argument you pass the number of files; this refers to the number of encypted files that will be created into a directory. In the Access Control Log Monitoring, you are also giving as argument the number of files; in this case you should check whether at least &lt;number of files&gt; have been produced within the last 20 minutes, and then print the number of files that have been produced within this time period, either with suffix “.encypt” or without. The idea behind this is: if in a system a large volume of files be created within a short time this will be considered suspicious and might correspond to a malicious case. In your implementation make sure that you print the total number of files created within the last 20 minutes; if this number is smaller than the &lt;number of files&gt;, then this does not indicate a suspicious behavior.</li>
<li>As arguments should be the name of a directory, and the number of files that will be created with your script. We repeat: do not use your existing files because you might corrupt them.</li>
<li>Your ransomware should have 2 operations: one is encrypting X files, and the other is creating a large volume of files. You can combine them i.e. creating X encrypted files within 20 minutes, but also separate these operations so as each of them will run individually. To implement selecting one of these 2 operations you can do it either via arguments, or, by calling the</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
ransomware and selecting the corresponding operation from a menu. Choose whatever

implementation you wish, and describe this briefly in your README.txt.

<ol start="13">
<li>Your ransomware could also support decryption operation. For example, add an argument in
your ransomware.sh that will be indicating the operation to run, i.e. creation of files and

then encryption, or, decryption of files. Describe this briefly in you README.txt.
</li>
<li>For the encryption/decryption use whatever algorithm you want. Describe this in your
README.txt.
</li>
</ol>
</div>
</div>
</div>
