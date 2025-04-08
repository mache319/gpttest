<!doctype html>
<html lang="ko">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>중고마켓</title>
  <link rel="stylesheet"
    href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
    crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
    crossorigin="anonymous"></script>
  <style>
    .preview-img {
      max-width: 100%;
      height: auto;
      margin-top: 10px;
    }

    .card {
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body>
  <!-- Hero -->
  <div class="hero bg-dark text-white text-center py-5 mb-5">
    <h1 class="display-4">중고 마켓</h1>
    <p class="lead">중고 물건 팝니다!</p>
  </div>

  <!-- 기존 샘플 카드들 -->
  <div class="container mt-4">
    <div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col">
        <div class="card h-100">
          <a href="https://www.coupang.com" target="_blank">
            <img src="data:image/jpeg;base64,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" class="card-img-top" alt="전기밥솥">
          </a>
          <div class="card-body">
            <h5 class="card-title">전기밥솥</h5>
            <h6 class="card-subtitle mb-2 text-muted">5만원</h6>
            <p class="card-text">한 번 밖에 안쓰는 전기밥솥 팝니다. 부모님이 독립 할 때 주신 거에요!</p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <a href="https://www.coupang.com" target="_blank">
            <img src="data:image/jpeg;base64,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" class="card-img-top" alt="치킨테이블">
          </a>
          <div class="card-body">
            <h5 class="card-title">치킨 테이블</h5>
            <h6 class="card-subtitle mb-2 text-muted">3만원</h6>
            <p class="card-text">혼술할 때 쓰던 테이블입니다. 튼튼해요!</p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <a href="https://www.coupang.com" target="_blank">
            <img src="data:image/jpeg;base64,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" class="card-img-top" alt="나무의자">
          </a>
          <div class="card-body">
            <h5 class="card-title">나무 의자</h5>
            <h6 class="card-subtitle mb-2 text-muted">2만원</h6>
            <p class="card-text">카페 분위기 나는 원목 의자 팝니다. 약간 기스 있음.</p>
          </div>
        </div>
      </div>
      <!-- 내 카드: 토스터기 -->
      <div class="col">
        <div class="card h-100">
          <img src="data:image/jpeg;base64,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" class="card-img-top" alt="토스터기">
          <div class="card-body">
            <h5 class="card-title">토스터기</h5>
            <h6 class="card-subtitle mb-2 text-muted">2만원</h6>
            <p class="card-text">잘 작동하는 토스터기입니다. 간단한 아침 식사에 좋아요!</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- 이미지 업로드 및 입력 폼 -->
  <div class="container my-5">
    <div class="row g-3">
      <div class="col-md-4">
        <label class="form-label">상품 이미지</label>
        <input type="file" class="form-control" id="imgInput">
        <img id="preview" class="preview-img" src="#" alt="미리보기" style="display:none;">
      </div>
      <div class="col-md-4">
        <label class="form-label">상품명</label>
        <input type="text" class="form-control" id="titleInput" placeholder="예: 전기밥솥">
        <label class="form-label mt-2">가격</label>
        <input type="text" class="form-control" id="priceInput" placeholder="예: 5만원">
      </div>
      <div class="col-md-4">
        <label class="form-label">상품 설명</label>
        <textarea class="form-control" id="descInput" rows="5" placeholder="상품 상태나 특징을 적어주세요."></textarea>
        <button class="btn btn-primary mt-2 w-100" onclick="addCard()">등록</button>
      </div>
    </div>
  </div>

  <!-- 동적으로 추가될 카드들 -->
  <div class="container mb-5">
    <div class="row row-cols-1 row-cols-md-3 g-4" id="cardList">
    </div>
  </div>

  <script>
    const imgInput = document.getElementById("imgInput");
    const preview = document.getElementById("preview");
    let imageDataURL = "";

    imgInput.addEventListener("change", function () {
      const file = imgInput.files[0];
      const reader = new FileReader();
      reader.onload = function (e) {
        imageDataURL = e.target.result;
        preview.src = imageDataURL;
        preview.style.display = "block";
      };
      if (file) reader.readAsDataURL(file);
    });

    function addCard() {
      const title = document.getElementById("titleInput").value;
      const price = document.getElementById("priceInput").value;
      const desc = document.getElementById("descInput").value;

      if (!title || !price || !desc || !imageDataURL) {
        alert("모든 정보를 입력해주세요!");
        return;
      }

      const cardHTML = `
        <div class="col">
          <div class="card h-100">
            <a href="https://www.coupang.com" target="_blank">
              <img src="${imageDataURL}" class="card-img-top" alt="${title}">
            </a>
            <div class="card-body">
              <h5 class="card-title">${title}</h5>
              <h6 class="card-subtitle mb-2 text-muted">${price}</h6>
              <p class="card-text">${desc}</p>
            </div>
          </div>
        </div>
      `;

      document.getElementById("cardList").insertAdjacentHTML("beforeend", cardHTML);

      document.getElementById("titleInput").value = "";
      document.getElementById("priceInput").value = "";
      document.getElementById("descInput").value = "";
      preview.src = "#";
      preview.style.display = "none";
      imageDataURL = "";
      imgInput.value = "";
    }
  </script>
</body>

</html>
