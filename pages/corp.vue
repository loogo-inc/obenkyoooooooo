<template>
  <div>
    <div class="catch">
      <h2><span class="under">俺がナンバーワン！</span></h2>
      <p>ここにキャッチコピーが入ります。<br />お店の宣伝やコンセプトなど。魅せる文言を入力。</p>
    </div>

    <section id="1" class="gray-back">
      <h2 class="center"><span class="under">商品について</span></h2>
      <div class="container center">
        <div class="row">
          <div class="col span-4">
            <img src="img/product.jpg" alt="ここに商品" />
            <h3>ここに商品が入ります</h3>
            <p>ここに説明文が入ります</p>
          </div>
          <div class="col span-4">
            <img src="img/product.jpg" alt="ここに商品" />
            <h3>ここに商品が入ります</h3>
            <p>ここに説明文が入ります</p>
          </div>
          <div class="col span-4">
            <img src="img/product.jpg" alt="ここに商品" />
            <h3>ここに商品が入ります</h3>
            <p>ここに説明文が入ります</p>
          </div>
        </div>
      </div>
    </section>

    <section id="2">
      <h2 class="center"><span class="under">スタッフ紹介</span></h2>
      <div class="container center">
        <div class="row">
          <div class="col span-4">
            <img src="img/staff.jpg" alt="スタッフ" />
            <h3>スタッフ</h3>
            <p>ここに説明文が入ります</p>
          </div>
          <div class="col span-4">
            <img src="img/staff.jpg" alt="スタッフ" />
            <h3>スタッフ</h3>
            <p>ここに説明文が入ります</p>
          </div>
          <div class="col span-4">
            <img src="img/staff.jpg" alt="スタッフ" />
            <h3>スタッフ</h3>
            <p>ここに説明文が入ります</p>
          </div>
        </div>
      </div>
    </section>

    <section id="3" class="gray-back">
      <h2 class="center"><span class="under">申し込みの流れ</span></h2>
      <div class="container">
        <div class="row flow">
          <div class="col span-3">
            <img src="img/flow.jpg" alt="申し込み" />
          </div>
          <div class="col span-9">
            <p>ここに文章が入ります。ここに文章が入ります。ここに文章が入ります。</p>
          </div>
        </div>
        <div class="row flow">
          <div class="col span-3">
            <img src="img/flow.jpg" alt="申し込み" />
          </div>
          <div class="col span-9">
            <p>ここに文章が入ります。ここに文章が入ります。ここに文章が入ります。</p>
          </div>
        </div>
        <div class="row flow">
          <div class="col span-3">
            <img src="img/flow.jpg" alt="申し込み" />
          </div>
          <div class="col span-9">
            <p>ここに文章が入ります。ここに文章が入ります。ここに文章が入ります。</p>
          </div>
        </div>
      </div>
    </section>

    <section id="4">
      <h2 class="center"><span class="under">アクセス</span></h2>
      <div class="container">
        <div class="row">
          <div class="col span-12">
            <!-- GoogleMap -->
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d27814443.96425483!2d120.28897720705172!3d31.679877148840735!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34674e0fd77f192f%3A0xf54275d47c665244!2z5pel5pys!5e0!3m2!1sja!2sjp!4v1555153587836!5m2!1sja!2sjp"
              width="100%"
              height="450"
              frameborder="0"
              style="border: 0"
              allowfullscreen
            ></iframe>
            <!-- /GoogleMap -->
          </div>
        </div>
      </div>
    </section>

    <section id="5">
      <h2 class="center"><span class="under">お問い合わせ</span></h2>
      <div class="container">
        <div class="row">
          <div class="col span-6">
            <div class="contact-box">
              <p><img src="img/tel.png" alt="電話" /></p>
              <p>012-345-6789</p>
            </div>
          </div>
          <div class="col span-6">
            <div class="contact-box">
              <p><img src="img/mail.png" alt="Eメール" /></p>
              <p>simple@mail.com</p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col span-12">
            <form method="post" action="">
              <table class="table full-width">
                <tbody>
                  <tr>
                    <th><label for="name">お名前</label></th>
                    <td>
                      <input
                        class="full-width"
                        type="text"
                        name="お名前"
                        placeholder="名前を記入"
                        id="exampNameInput"
                      />
                    </td>
                  </tr>
                  <tr>
                    <th><label for="email">メールアドレス</label></th>
                    <td>
                      <input
                        class="full-width"
                        type="email"
                        name="Email"
                        placeholder="メールアドレスを記入"
                        id="exampleEmailInput"
                      />
                    </td>
                  </tr>
                  <tr>
                    <th><label for="tel">お電話番号</label></th>
                    <td>
                      <input
                        class="full-width"
                        type="tel"
                        name="お電話番号"
                        placeholder="お電話番号を記入"
                        id="exampleTellInput"
                      />
                    </td>
                  </tr>
                  <tr>
                    <th><label for="exampleMessage">お問い合わせ内容</label></th>
                    <td>
                      <textarea
                        class="full-width textarea"
                        name="お問い合わせ内容"
                        placeholder="用件をご記入ください …"
                        id="exampleMessage"
                      ></textarea>
                    </td>
                  </tr>
                </tbody>
              </table>
              <p class="center"><input class="button" type="submit" value="送 信" /></p>
            </form>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  components: {
  }
}
</script>
