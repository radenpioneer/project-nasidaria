<div class="player">
  <div class="album-art"></div>
  <div class="text">
    <span class="title">Judul Lagu</span>
    <span>Nama Artis</span>
  </div>
</div>

<style lang="scss">
  .player {
    min-height: 90vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1.5rem;
    padding: 2rem 2rem;

    .album-art {
      width: 100%;
      aspect-ratio: 1/1;
      background-color: #bbbbbb;
    }

    .text {
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      width: 100%;

      .title {
        font-weight: 700;
        font-size: 1.5rem;
      }
    }
  }
</style>
