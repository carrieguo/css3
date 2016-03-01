# css3
响应式 布局
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Internal Directory</title>
    <style>
        html{ font-size: 16px;}
        body{
            font-size: 16px;
            font-family: "Microsoft YaHei","open sans",Arial,\5FAE\8F6F\96C5\9ED1,STHeiti !important;
        }
        .main{ max-width: 1440px; margin: 0 auto;}
        .main-content{width: 1200px; margin: 0 auto;}
        table{  border-collapse: collapse;}
        table tr th{ padding:10px 25px; text-align: center; font-weight: 600; color: #292F21;}
        table tr td{ padding:10px 25px; color: #333333;}
        table tr td:first-child{ color: #999999; text-align: center;}
        table tr td{ text-align: right;}
        table tr:nth-child(odd){background:#F4F4F4;}
        table tr:hover{ background: #E6E6E6;}
        thead>tr{ background-color: #60BF19!important;}
        @media (max-width: 1100px){
            .main-content{ width: auto;}
            table, thead, tbody, th, td, tr {  display: block;}
            thead tr {  position: absolute;  top: -9999px;  left: -9999px;}
            tr { border: 1px solid #ccc;}
            td {  border: none;  border-bottom: 1px solid #eee;  position: relative;  padding-left: 50%!important;}
            td:before {  position: absolute;  top: 6px;  left: 6px;  width: 45%;  padding-right: 10px!important;  white-space: nowrap;}
            td:nth-of-type(1):before { content: "Name"; }
            td:nth-of-type(2):before { content: "Extension"; }
            td:nth-of-type(3):before { content: "Mobile"; }
            td:nth-of-type(4):before { content: "International"; }
            td:nth-of-type(5):before { content: "Email"; }
            td:nth-of-type(6):before { content: "Birthday"; }
            table tr td:first-child{ text-align: left;}
            table tr td{ text-align: left;}
        }
        @media (max-width: 425px){
            body{ font-size: 12px;}
            td{ padding-left: 40%!important;}
        }
    </style>
</head>
<body>
<div class="main">
    <div class="main-content">
        <h1>Internal Directory</h1>
        <table>
            <thead>
            <tr class="title"><th>Name</th><th>Extension</th><th>Mobile</th><th>International</th><th>Email</th><th>Birthday</th></tr>
            </thead>
            <tbody>
            </tbody>

        </table>
    </div>
</div>
</body>
</html>
