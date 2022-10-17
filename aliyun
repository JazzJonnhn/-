let a1 = JSON.parse($response.body);
if (a1.result) {
    a1.result = Object.values(a1.result).filter(item => (item["appCode"]=="file"));
}
$done({ body: JSON.stringify(a1) });
