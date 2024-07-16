::

   pgcopydb stream sentinel set endpos: Set the sentinel end position LSN
   usage: pgcopydb stream sentinel set endpos [ <end lsn> | --current ]
   
     --current     Use pg_current_wal_flush_lsn() as the endpos
   
