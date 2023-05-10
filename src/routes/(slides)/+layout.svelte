<script lang="ts">
  import 'animate.css';
  
  import { Deck, slides } from 'presveltation';

  $slides = [
      // no notes -> default notes are shown instead
      { route: '/00-intro', title: 'Introduction', notes: false },
      // notes are in /01-intro/notes route
      { route: '/01-song1', title: 'Song 1', notes: false }, 
      { route: '/02-song2', title: 'Song 2', notes: false },
      { route: '/03-song3', title: 'Song 3', notes: false }, 
      { route: '/04-song4', title: 'Song 4', notes: false },
      { route: '/05-song5', title: 'Song 5', notes: false }, 
      { route: '/06-song6', title: 'Song 6', notes: false },
      { route: '/07-song7', title: 'Song 7', notes: false }, 
      { route: '/08-song8', title: 'Song 8', notes: false },
      { route: '/09-song9', title: 'Song 9', notes: false }, 
      { route: '/10-song10', title: 'Song 10', notes: false }
  ]
</script>

<Deck notesURL="/notes">
  <slot />
</Deck>