<table class="e-rte-table">
   <thead>
      <tr>
         <th>ID</th>
         <th>Feature</th>
         <th>Description</th>
         <th>Preconditions</th>
         <th>Test data</th>
         <th>Steps</th>
         <th>Expected result</th>
         <th>Notes</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>TC-001</td>
         <td>Registration form</td>
         <td>Verify successful registration with valid data</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test001@gmail.com">Test001@gmail.com</a></td>
         <td>Email: <a href="mailto:Test001@gmail.com">Test001@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-002</td>
         <td>Registration form</td>
         <td>Verify successful registration with all allowed Email characters</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Te.st_002@Test-domain.123.com">Te.st_002@Test-domain.123.com</a></td>
         <td>Email: <a href="mailto:Te.st_002@Test-domain.123.com">Te.st_002@Test-domain.123.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data:<br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-003</td>
         <td>Registration form</td>
         <td>Verify successful registration with all allowed Password characters</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test003@gmail.com">Test003@gmail.com</a></td>
         <td>Email: <a href="mailto:Test003@gmail.com">Test003@gmail.com</a><br/>Password: Test_Pass@777!<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data:<br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-004</td>
         <td>Registration form</td>
         <td>Verify successful registration with all allowed Company characters</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test004@gmail.com">Test004@gmail.com</a></td>
         <td>Email: <a href="mailto:Test004@gmail.com">Test004@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: Test-Company004</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-005</td>
         <td>Registration form / Terms &amp; Conditions</td>
         <td>Verify registration attempt with unchecked ""Terms &amp; Conditions"" checkbox</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test005@gmail.com">Test005@gmail.com</a></td>
         <td>Email: <a href="mailto:Test005@gmail.com">Test005@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data:<br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error is displayed for the unchecked ""I accept the Terms &amp; Conditions"" checkbox</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-006</td>
         <td>Registration form / Country</td>
         <td>Verify registration attempt with Country not explicitly selected</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test006@gmail.com">Test006@gmail.com</a></td>
         <td>Email: <a href="mailto:Test006@gmail.com">Test006@gmail.com</a><br/>Password: testpassword<br/>Country: (not selected / left as is)<br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Company *<br/>2. Leave the ""Country"" field as is (do not select any value)<br/>3. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>4. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error is displayed for ""Country"" field</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-007</td>
         <td>Registration form / Email</td>
         <td>Verify registration attempt when entering an already registered Email</td>
         <td>Registration form is opened<br/>The user with Email <a href="mailto:Test007@gmail.com">Test007@gmail.com</a> already exists</td>
         <td>Email: <a href="mailto:Test007@gmail.com">Test007@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed (e.g. ""Email is already registered"")</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-008</td>
         <td>Registration form / Email</td>
         <td>Verify registration attempt with empty ""Your Email Address"" field</td>
         <td>Registration form is opened</td>
         <td>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Leave the ""Your Email Address"" field as is<br/>3. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>4. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed (e.g. ""Email cannot be empty"")</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-009</td>
         <td>Registration form / Email</td>
         <td>Verify registration with empty Email local part</td>
         <td>Registration form is opened</td>
         <td>Email: @gmail.com <br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-010</td>
         <td>Registration form / Email</td>
         <td>Verify registration with minimum Email local part length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:1@gmail.com">1@gmail.com</a></td>
         <td>Email: <a href="mailto:1@gmail.com">1@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-011</td>
         <td>Registration form / Email</td>
         <td>Verify registration with maximum Email local part length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa@gmail.com">aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa@gmail.com</a></td>
         <td>Email: <a href="mailto:aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa@gmail.com">aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-012</td>
         <td>Registration form / Email</td>
         <td>Verify registration with Email local part exceeding maximum length</td>
         <td>Registration form is opened</td>
         <td>Email: <a href="mailto:aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa1@gmail.com">aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa1@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-013</td>
         <td>Registration form / Email</td>
         <td>Verify registration with dot in invalid position in Email local part</td>
         <td>Registration form is opened</td>
         <td>Email: <a href="mailto:.Test013@gmail.com">.Test013@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-014</td>
         <td>Registration form / Email</td>
         <td>Verify registration with quoted Email local part containing consecutive dots</td>
         <td>Registration form is opened<br/>No existing user with Email ""Test..014""@gmail.com</td>
         <td>Email: ""Test..014""@gmail.com<br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-015</td>
         <td>Registration form / Email</td>
         <td>Verify registration without ""@"" symbol in Email</td>
         <td>Registration form is opened</td>
         <td>Email: Test015gmail.com<br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-016</td>
         <td>Registration form / Email</td>
         <td>Verify registration with hyphen in invalid position in Email domain</td>
         <td>Registration form is opened</td>
         <td>Email: <a href="mailto:Test016@-gmail.com">Test016@-gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-017</td>
         <td>Registration form / Email</td>
         <td>Verify registration with empty Email domain part</td>
         <td>Registration form is opened</td>
         <td>Email: Test017@<br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-018</td>
         <td>Registration form / Email</td>
         <td>Verify registration with minimum Email domain length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test018@a.b">Test018@a.b</a></td>
         <td>Email: <a href="mailto:Test018@a.b">Test018@a.b</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-019</td>
         <td>Registration form / Email</td>
         <td>Verify registration with maximum Email domain length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test019@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.a">Test019@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.a</a></td>
         <td>Email: <a href="mailto:Test019@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.a">Test019@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.a</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-020</td>
         <td>Registration form / Email</td>
         <td>Verify registration with Email domain exceeding maximum length</td>
         <td>Registration form is opened</td>
         <td>Email: <a href="mailto:Test020@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.aa">Test020@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.aa</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-021</td>
         <td>Registration form / Email</td>
         <td>Verify registration with dot in invalid position in Email domain</td>
         <td>Registration form is opened</td>
         <td>Email: Test021@gmailcom.<br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-022</td>
         <td>Registration form / Email</td>
         <td>Verify registration with Email containing non-Latin characters</td>
         <td>Registration form is opened</td>
         <td>Email: Тест<a href="mailto:022@gmail.com">022@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-023</td>
         <td>Registration form / Email</td>
         <td>Verify registration with Email containing multiple ""@"" symbols</td>
         <td>Registration form is opened</td>
         <td>Email: Test023@<a href="mailto:gmail@mail.com">gmail@mail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-024</td>
         <td>Registration form / Email</td>
         <td>Verify registration with Email containing spaces</td>
         <td>Registration form is opened</td>
         <td>Email: Test <a href="mailto:024@gmail.com">024@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Your Email Address"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-025</td>
         <td>Registration form / Password</td>
         <td>Verify registration with empty Password</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test025@gmail.com">Test025@gmail.com</a></td>
         <td>Email: <a href="mailto:Test025@gmail.com">Test025@gmail.com</a><br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Country *<br/>- Company *<br/>2. Leave the ""Password"" field as is<br/>3. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>4. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Password"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-026</td>
         <td>Registration form / Password</td>
         <td>Verify registration with Password containing non-Latin characters</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test026@gmail.com">Test026@gmail.com</a></td>
         <td>Email: <a href="mailto:Test026@gmail.com">Test026@gmail.com</a><br/>Password: тестпароль<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Password"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-027</td>
         <td>Registration form / Password</td>
         <td>Verify registration with Password of minimum length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test027@gmail.com">Test027@gmail.com</a></td>
         <td>Email: <a href="mailto:Test027@gmail.com">Test027@gmail.com</a><br/>Password: 12345678<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-028</td>
         <td>Registration form / Password</td>
         <td>Verify registration with Password of maximum length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test028@gmail.com">Test028@gmail.com</a></td>
         <td>Email: <a href="mailto:Test028@gmail.com">Test028@gmail.com</a><br/>Password: 1234567812345678<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-029</td>
         <td>Registration form / Password</td>
         <td>Verify registration with Password exceeding maximum length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test029@gmail.com">Test029@gmail.com</a></td>
         <td>Email: <a href="mailto:Test029@gmail.com">Test029@gmail.com</a><br/>Password: 1234567812345678gbh<br/>Country: Ukraine <br/>Company: company</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Password"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-030</td>
         <td>Registration form / Company</td>
         <td>Verify registration with empty Company field</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test030@gmail.com">Test030@gmail.com</a></td>
         <td>Email: <a href="mailto:Test030@gmail.com">Test030@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>2. Leave the ""Company"" field as is<br/>3. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>4. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Company"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-031</td>
         <td>Registration form / Company</td>
         <td>Verify registration with Company name of minimum length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test031@gmail.com">Test031@gmail.com</a></td>
         <td>Email: <a href="mailto:Test031@gmail.com">Test031@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: abc</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-032</td>
         <td>Registration form / Company</td>
         <td>Verify registration with Company name of maximum length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test032@gmail.com">Test032@gmail.com</a></td>
         <td>Email: <a href="mailto:Test032@gmail.com">Test032@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>User is successfully registered; no validation errors<br/></td>
         <td>Delete the user after test</td>
      </tr>
      <tr>
         <td>TC-033</td>
         <td>Registration form / Company</td>
         <td>Verify registration with Company name exceeding maximum length</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test033@gmail.com">Test033@gmail.com</a></td>
         <td>Email: <a href="mailto:Test033@gmail.com">Test033@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa1</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Company"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-034</td>
         <td>Registration form / Company</td>
         <td>Verify registration with Company name containing special characters</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test034@gmail.com">Test034@gmail.com</a></td>
         <td>Email: <a href="mailto:Test034@gmail.com">Test034@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: Company@%!</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Company"" field is displayed</td>
         <td><br/></td>
      </tr>
      <tr>
         <td>TC-035</td>
         <td>Registration form / Company</td>
         <td>Verify registration with Company name containing non-Latin characters</td>
         <td>Registration form is opened<br/>No existing user with Email <a href="mailto:Test035@gmail.com">Test035@gmail.com</a></td>
         <td>Email: <a href="mailto:Test035@gmail.com">Test035@gmail.com</a><br/>Password: testpassword<br/>Country: Ukraine <br/>Company: компанія</td>
         <td>1. Fill in all fields with the test data: <br/>- Your Email Address *<br/>- Password *<br/>- Country *<br/>- Company *<br/>2. Check the checkbox ""I accept the Terms &amp; Conditions"" <br/>3. Click the ""Register"" button</td>
         <td>Registration is not completed; validation error for ""Company"" field is displayed</td>
         <td><br/></td>
      </tr>
   </tbody>
</table>
